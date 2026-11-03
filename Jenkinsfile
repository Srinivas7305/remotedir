pipeline {
  agent any

  stages {
    stage ('Build') {
      steps {
        echo "This is a build stage"

      }
     }
      stage ('Tests') {
        parallel {
    stage ('unit test') {
    steps {
    echo "This is Unit Test"
    }
    }
    stage ('App Test') {
    steps {
      echo "This is App Test"
    }
    }
      stage ('UI Test') {
    steps {
      echo "This is UI Test"
    }
    }
  }
}
  }
}
    
