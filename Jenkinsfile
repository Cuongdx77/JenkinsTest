podTemplate(yaml: readTrusted('pod.yaml')) {
  node(POD_LABEL) {
    stage('Run Test') {
      container('jnlp') {
        stage('Shell Execution') {
          sh 'tail -f /dev/null'
        }
      }
    }
  }
}
