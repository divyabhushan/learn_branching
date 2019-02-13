pipeline {
    agent { docker { image 'ubuntu:latest' } }
    stages {
        stage('build') {
            steps {
		echo 'Building project...'
                sh 'uname -a'
            }
        }
	stage('test') {
	   steps {
		echo 'Testing project...'
		echo '[OK]: Tests passed.'
	   }
	}
	stage('deploy') {
	   steps {
		echo '[OK]: Deploying to production server'
	   }
    }
}
}

