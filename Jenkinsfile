node {
    checkout scm
    stage('Build') {
    	sh 'source /Users/pguo/.zshenv'
        docker.image('maven:3.3.3').inside {
            sh 'mvn --version'
        }
    }
}