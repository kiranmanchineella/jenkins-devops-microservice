pipeline{
	agent any
	stages{
		stage('Build') {
			steps {
				echo "Build"
			}
		}
		stage("Test") {
			steps{
			echo 'Test'
			}
		}
		stage('Integration Test')
		steps{
			echo 'Integration test'
		}
	}post{
	always{
		echo 'kiran the KING Manchineella'
	}
	success {
		echo 'Success'
	}
	failure {
		echo "fail"
	}
  }  
}