pipeline {
  agent {
    docker {
      image 'node:alpine'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'sh \'npm --version\''
      }
    }
  }
}