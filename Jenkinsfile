//Declarative

pipeline{
	agent {docker{image 'maven:3.6.3'}}
	stages{
		stage('Build'){
			steps{
				sh 'mvn --version'
			}
		}
		stage('Test'){
			steps{
				echo "Test"
			}
		}
		stage('Integration Test'){
			steps{
				echo "Integration Test"
			}
		}
	}
	post{
		success{
			echo"Build successfull"
		}
	}
}
