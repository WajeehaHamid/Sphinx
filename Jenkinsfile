Jenkinsfile (Declarative pipeline)
pipeline {
    agent { docker 'python:3.5.1' }
    stages {
        stage('build') {
            steps {
		python './pytest.py'
            }
        }
    }
}