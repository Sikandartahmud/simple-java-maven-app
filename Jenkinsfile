pipeline {
    agent any

    stages {
        stage('PrepareEnvironment') {
            steps {
                echo 'Preparing the deployment environment'
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
