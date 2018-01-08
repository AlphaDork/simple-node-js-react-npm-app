pipeline {
  agent {
    docker {
      args '-p 3000:3000'
      image 'alphadork/node-base'
    }
    
  }
  stages {
    stage('Build') {
      steps {
        sh 'sh \'npm install\''
      }
    }
  }
}