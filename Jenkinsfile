pipeline{
	agent any
	
	stages{
		stage('Nunit Test Project'){
			steps{
				echo 'Nunit Test Project'
			}
		}
		stage('Buld'){
			steps{
				build 'https://github.com/gmurad99/NunitTestProject.git'
				echo 'Build the project'
			}
		}
		stage('Test'){
			steps{
				echo'test the project'
			    }
		
		}
	
	  }

}
