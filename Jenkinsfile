pipeline {
  agent none
  stages {
    stage('windows') {
      agent { label 'windows' }
      steps { sh 'uname -a' }
    }
    stage('Windows check') {
      agent { label 'windows' }
      steps { bat 'ver' }
    }
  }
}
