pipeline {
    agent any
    stages {
        stage('build') {
            steps {
            	docker info
                echo sh(returnStdout: true, script: 'env')
            }
        }
    }
}