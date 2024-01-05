podTemplate(yaml: readTrusted('pod.yaml')) {
  node(POD_LABEL) {
     stage('Run Test') {
            container('test') {
                stage('Shell Execution') {
                    sh 'sleep infinity' 
                }
            }
        }
  }
}
