pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'pip install -r requirements.txt'
      }
    }

    stage('Test') {
      steps {
        echo 'Hello World I am started'
      }
    }

  }
}