pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'npm install'
      }
    }

  }
  environment {
    Image = 'node:6-alpine'
    Args = '-p 3000:3000'
  }
}