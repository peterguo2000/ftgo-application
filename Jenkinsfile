pipeline {
    agent { docker { image 'maven:3.3.3' } }
    stages {
        stage('build') {
            steps {
            	docker info
                echo sh(returnStdout: true, script: 'env')
            }
        }
    }
}