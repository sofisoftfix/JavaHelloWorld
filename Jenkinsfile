pipeline {
	agent any
	stages {
		stage("Build") {
			steps {
				// get code from repository
				git url: 'https://github.com/sofisoftfix/JavaHelloWorld.git', branch: 'master',
				credentialsId: '86c5284a-7ab9-4166-972f-94f83b9c256e'
				}
			}
		}
	}
