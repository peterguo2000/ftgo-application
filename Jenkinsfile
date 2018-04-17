pipeline {
    agent any
    stages {
        stage('build') {
            steps {
            	sh '/usr/local/bin/docker info'
                echo sh(returnStdout: true, script: 'env')
            }
        }
    }
}