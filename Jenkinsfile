pipeline {
    agent {
        docker { image 'node:20.9.0-alpine3.18' }
    }
    environment {
        TZ = 'Asia/Seoul'
    }
    stages {
        stage('Test') {
	    steps {
	        sh 'node --version'
		sh 'echo $TZ'
            }
        }
    }
}
