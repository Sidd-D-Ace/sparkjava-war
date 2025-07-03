pipeline{
	agent any
	environment{
		PATH = "/opt/apache-maven-3.9.10/bin:$PATH"
	}
	stages{
		stage("Welcome"){
			steps{
				echo "Welcome User"
			}
				
		stage("Building"){
			steps{
				sh 'mvn clean install'
			}
		}
	}
}
