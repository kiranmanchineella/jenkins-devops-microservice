pipeline {
	agent any
	    stages {
		    stage('Build'){
			
		            steps{
                           echo "Build"
	           

		               }
	               }
   
               stage('Test'){
		          steps{
                           echo "Test" 
		                }
			   }      
                stage('Integration test'){
		              steps{
               
	                       echo "Integration Test"
		                   }
			 }
       }  post{ 
		   always{
			   echo 'kiran the KING Manchineella'
		   }
		   success{
			   echo 'success'
		   }
		   failure{
			   echo 'fail'
		   }
	}
}