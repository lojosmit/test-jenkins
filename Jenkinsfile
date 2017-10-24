pipeline {
	agent { docker 'maven:3.3.5'}
	stages{
		stage('build') {
			steps{
				sh 'mvn --version'
			}
		}
	}
}
