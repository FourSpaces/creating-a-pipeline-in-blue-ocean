pipeline {
  agent {
    docker {
      image 'node:6-alpine'
      args '-p 3030:3000'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'npm install'
      }
    }

  }
}