pipeline {
    agent {
        label 'master'
    }
    stages {
        stage('build') {
            steps {
                echo sh(returnStdout: true, script: 'env')
                sh 'docker info'
            }
        }
    }
}