pipeline {
	agent {docker {image 'maven:3.6.3'}} 
	stages { 
		stage('Build') {
			steps {
				sh 'mvn --version'
				echo "Build"
			}
		}
		stage('Test') {
			steps{
			echo "Test"
			}
		}
		stage('Integration Test') {
		steps{
			echo "Integration test"
		}
	}
	}
	post{
	always{
		echo "kiran the KING Manchineella"
	}
	success {
		echo "Success"
	}
	failure {
		echo "I run when fail"
	}
  }  
}
