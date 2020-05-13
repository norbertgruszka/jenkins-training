

node {
	checkout scm

	docker.image("python:3.7-slim-buster").inside {
		stage('Test') {
			sh 'tox'
		}
	}
}

