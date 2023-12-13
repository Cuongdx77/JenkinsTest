pipeline {
  agent {
    docker { image 'alpine:latest' }
  }
  stages {
    stage('Test') {
      steps {
        sh 'echo "Welcome to Alpine"'
        sh 'docker run alpine:latest echo "Running command inside another Alpine container"'
      }
    }
  }
}
