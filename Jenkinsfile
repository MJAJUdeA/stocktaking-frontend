pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'npm install'
        nodejs('Node 14.4') {
          sh 'npm --version'
        }

      }
    }

  }
}