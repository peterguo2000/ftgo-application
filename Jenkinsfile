pipeline {
    agent {
        label 'master'
    }
    stages {
        stage('build') {
            steps {
                echo sh(returnStdout: true, script: 'env')
                sh 'ln -f -s /Applications/Docker.app/Contents/Resources/bin/* /usr/local/bin'
                sh 'docker info'
            }
        }
    }
}