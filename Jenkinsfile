node {
    checkout scm
    stage('Build') {
    	echo sh(returnStdout: true, script: 'env')
        withEnv(["PATH=/usr/bin:/bin:/usr/sbin:/sbin:/Applications/Docker.app/Contents/Resources/bin:/usr/local/bin"]) {  
            docker.image('maven:3.3.3').inside {
                sh 'mvn --version'
            }
        }  
    }
}