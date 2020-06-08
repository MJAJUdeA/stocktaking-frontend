pipeline {
  agent {
    node {
      label 'node'
    }

  }
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
  environment {
    NODEJS_HOME = '${tool \'Node 14.4\'}'
  }
}