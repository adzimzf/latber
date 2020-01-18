pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        sh 'git clone git@github.com:adzimzf/sks.git'
      }
    }

    stage('Test') {
      steps {
        sh 'echo "testing"'
      }
    }

  }
}