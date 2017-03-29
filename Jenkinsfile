pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'cat README.md'
      }
    }
    stage('Test') {
      steps {
        sh 'echo "Test"'
      }
    }
  }
}