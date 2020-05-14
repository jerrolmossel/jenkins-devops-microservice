//SCRIPTED

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
				echo "Test"
			}
		}
				stage('Integration Test') {
			steps {
				echo "Integration Test"
			}
		}
	} post {
		always {
			'I am awesome. I run always'
		}
		success {
			'I run when you are successful'
		}
		failure {
			'I run when you fail'
		}
	}
}