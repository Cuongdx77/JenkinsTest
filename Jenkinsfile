podTemplate(containers: [
    containerTemplate(
        name: 'nginx', 
        image: 'nginx:latest'
        )
  ]) {

    node(POD_LABEL) {
        stage('Run Test') {
            container('nginx') {
                stage('Shell Execution') {
                    sh 'sleep infinity' 
                }
            }
        }

    }
}
