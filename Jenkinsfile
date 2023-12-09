pipeline {
  agent any
  stages {
    stage('Message') {
      steps {
        echo 'Hello Worl !'
      }
    }

    stage('build') {
      steps {
        sh 'npm install'
      }
    }

  }
}