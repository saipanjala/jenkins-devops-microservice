//DECLARATIVE
pipeline {
	agent any
	stages {
		stage('Build') {
			steps {
				echo "Build"
			}
		}
		stage('Test') {
			steps {
				echo "Tes"
			}
		}
		stage('Integration Test') {
			steps {
				echo "Integration Test"
			}
		}
	}
	post
	{
		always {
			echo 'Im awesome. I run always'
		}
		success {
			echo 'Im run when you are successful'
		}
		failure {
			echo 'I run when you fail'
		}
	}
}


