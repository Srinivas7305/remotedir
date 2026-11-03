pipeline {
   agent {
      label 'linux'
   }
    stages {
    stage ('showinput') {
      steps {
     script {
        def branchName = env.BRANCHNAME
        echo "branch name ${branchName}"

        if (branchName == 'main) {
            echo "production"
        }
            else if (branchName == 'develop') {
               echo "RUN UAT"
            }else {
               echo "validation"
            }
      }
    }
  }
}
            }
