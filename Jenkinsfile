pipeline {
  agent {
    docker {
      image 'node:6-apline'
      args '-p 3000:3000'
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
