pipeline{
	agent any
	stages {
		stage ('Initial') {
		steps{
		echo 'Starting phase'
		
		}
		}
		stage ('Build') {
		steps{
			git 'mvn clean package'
		
		}
		}
		
	}}
