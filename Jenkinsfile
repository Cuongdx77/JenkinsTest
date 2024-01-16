podTemplate(yaml: readTrusted('pod.yaml')) {
  node(POD_LABEL) {
    stage('Run Test') {
      container('jnlp') {
        stage('Shell Execution') {
          sh 'sleep 2h'
        }
      }
    }
  }
}
