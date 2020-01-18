pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        sh 'git clone https://github.com/trie168/health-care-backend.git'
      }
    }

    stage('Test') {
      steps {
        sh 'echo "testing"'
      }
    }

  }
}