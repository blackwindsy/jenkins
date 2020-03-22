pipeline {
	agent any
	stages {
		stage('init') {
			echo('init start')
			echo("JENKINS_URL = ${env.JENKINS_URL}") 
			echo("Running ${env.BUILD_ID} ${env.BUILD_NUMBER}") 
			echo("BUILD_URL = ${env.BUILD_URL}") 
			echo("WORKSPACE = ${env.WORKSPACE}") 
			echo('init end')
		}
		stage('build') {
			echo('build start')
			echo('build end')
		}
		stage('deploy') {
			echo('deploy start')
			echo('deploy end')
		}
		stage('result') {
			echo('result start')
			echo('result end')
		}
	}
}
