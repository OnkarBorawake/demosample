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
			withMaven(maven : 'apache-maven-3.6.3') {
			bat 'mvn clean package'
		
		}
		}
		
	}}
