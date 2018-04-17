node {
    checkout scm
    stage('Build') {
    	echo sh(returnStdout: true, script: 'env')
    	sh 'source /Users/pguo/.zshenv'
    	echo sh(returnStdout: true, script: 'env')
    	
        docker.image('maven:3.3.3').inside {
            sh 'mvn --version'
        }
    }
}