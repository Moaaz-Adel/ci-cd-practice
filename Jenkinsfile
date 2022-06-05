pipeline {
  agent any
  stages {
    stage('Starting') {
      steps {
        retry(count: 1) {
          echo 'Starting Pipe'
        }

        echo 'step 1'
      }
    }

    stage('Test') {
      steps {
        echo 'Test Stage'
      }
    }

  }
}