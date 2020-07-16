pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        build 'build-job'
      }
    }

    stage('Test') {
      steps {
        echo 'Test passed'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Successfully deployed'
      }
    }

  }
}