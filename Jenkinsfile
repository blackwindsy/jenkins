pipeline {
	agent any
	stages {
		stage('init') {
			steps {
				echo('init start')
				echo("JENKINS_URL = ${env.JENKINS_URL}") 
				echo("Running ${env.BUILD_ID} ${env.BUILD_NUMBER}") 
				echo("BUILD_URL = ${env.BUILD_URL}") 
				echo("WORKSPACE = ${env.WORKSPACE}") 
				echo('init end')
			}
		}
		stage('build') {
			steps {
				echo('build start')
				echo('build end')
			}
		}
		stage('deploy') {
			steps {
				echo('deploy start')
				echo('deploy end')
			}
		}
		stage('result') {
			steps {
				echo('result start')
				echo('result end')
			}
		}
	}
}
