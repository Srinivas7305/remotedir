pipeline {
  agent none

  stages {
    stage ('windows Stage') {
      agent {
        label 'windows'
     }
      steps { 
        bat 'echo Hello from windows'
      bat 'whoami'
        
      }
    }

    stage ('Linux stage') {
      agent {
        label 'linux'
  }
      steps {
        sh 'echo Hello from Linux'
        sh 'whoami'
}
    }
  }
}
