pipeline {
  agent {
    docker { image 'alpine:latest' }
  }
  stages {
    stage('Test') {
      steps {
        sh 'echo "Welcome to Alpine"'
        sh 'docker run alpine:latest '
        sh 'echo "Runing success"'
      }
    }
  }
}
