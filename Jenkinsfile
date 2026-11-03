pipeline {
  agent any

  stages {
    stage ('Build') {
      steps {
        echo "This is a build stage"

      }
     }
      
    stage ('unit test') {
    steps {
      sh 'sleep 3'
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
    
