pipeline {
    agent { docker { image 'maven:3-alpine' 
        			  args  '-v /tmp:/tmp'    				 
    					        } }
    stages {
        stage('build') {
            steps {
                echo sh(returnStdout: true, script: 'env')

            }
        }
    }
}