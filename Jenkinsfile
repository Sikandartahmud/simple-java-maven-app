pipeline {
    agent any

    stages {
        stage('PrepareEnvironment') {
            steps {
                sh '''
                chmod 777 scripts/prod.sh
                scripts/prod.sh
		ls -ltra /home/ubuntu
                '''
            }
        }
        stage('CopyConfig') {
            steps {
                echo 'Copy Config step is executing.'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....  This is the deployment phase'
            }
        }
	stage('Postdeploy') {
		steps {
			echo 'Postdeployment phase....'
		}
	}
    }
}
