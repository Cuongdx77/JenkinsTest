pipeline {
  agent {
    docker { image 'alpine:latest' }
  }
  stages {
    stage('Test') {
      steps {
        sh 'echo: "Welcome to alpine"'
      }
    }
  }
}
