pipeline{
	agent any
	environment{
		PATH = "/opt/apache-maven-3.9.10/bin:$PATH"
	}
	stages{
		stage("Building"){
			steps{
				sh 'mvn clean install'
			}
		}
	}
}
