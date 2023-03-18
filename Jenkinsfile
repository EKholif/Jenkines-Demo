pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'hello bob'
          }
        }

        stage('error') {
          steps {
            echo 'hello  helooo'
          }
        }

        
        stage('put') {
          steps {
            echo 'hello  helooo'
          }
        }

      }
    }

    stage('Maven 3.9.0') {
      steps {
        echo 'maven'
      }
    }

  stage('Maven 3.6.0') {
      steps {
        echo 'maven'
      }
    }
  }
}