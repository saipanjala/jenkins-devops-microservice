//DECLARATIVE
pipeline {
	agent { docker { image 'maven:3.6.3'} }
	stages {
		stage('Build') {
			steps {
				sh 'mv --version'
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


