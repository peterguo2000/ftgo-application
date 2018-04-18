node {
    checkout scm
    stage('Build') {
    	echo sh(returnStdout: true, script: 'env')
        withEnv(["PATH=/usr/bin:/bin:/usr/sbin:/sbin:/Applications/Docker.app/Contents/Resources/bin:/usr/local/bin"]) {  
            docker pull maven:3.3.3
        }  
    }
}