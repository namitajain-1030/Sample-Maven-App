pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        git 'https://github.com/cndacademy/Sample-Maven-App.git'
      }
    }

    stage('test') {
      steps {
        echo 'Hello from Test'
      }
    }

  }
}