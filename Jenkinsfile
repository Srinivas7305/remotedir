pipeline {
  agent any

  stages {
    stage ('Build') {
      agent {
        echo "This is a build stage"

      }
     }
      
    stage ('unit test') {
    steps {
    echo "This is Unit Test
    }
    }
    stage ('App Test') {
    steps {
      echo "This is a App Test"
    }
    }
      stage ('UI Test') {
    steps {
      echo "This is a UI Test"
    }
    }
  }
}
    
