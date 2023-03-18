pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'hello'
          }
        }

        stage('error') {
          steps {
            echo 'hello'
          }
        }

      }
    }

    stage('Maven 3.9.0') {
      steps {
        echo 'maven'
      }
    }

  }
}