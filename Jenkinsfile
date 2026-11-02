pipeline {
  agent {
    label'linux'
}
  
   stages {
     stage ('show input') {
       steps { 
         script {
           def branchName = env.BRANCH_NAME
           echo "Branch name ${branchName}

           if (branchName == "master') {
               echo "production" 
           }
               else if (branchName == 'develop') {
                 echo "RUN UAT"
                 }
               else {
                 echo "Validation"
               }

               }
         }
       }
     }
   }
