pipeline {
     agent {
        docker { image 'node:7-alpine' }
  stages {
      stage('Test') {
            steps {
                sh 'node --version'
                input message: 'Finished using the web site? (Click "Proceed" to continue)'
            }
           }
        }
    }
}

