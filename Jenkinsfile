pipeline {
  agent any
  stages {
    stage('Starting') {
      parallel {
        stage('Starting') {
          steps {
            retry(count: 1) {
              echo 'Starting Pipe'
            }

            echo 'step 1'
          }
        }

        stage('Parallel') {
          steps {
            echo 'Running Parallel'
          }
        }

      }
    }

    stage('Test') {
      steps {
        echo 'Test Stage'
      }
    }

  }
}