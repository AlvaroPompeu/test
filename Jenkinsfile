pipeline {
    agent any
    parameters {
	string(name: 'ID', defaultValue: '01', description: 'foo')
    }
    stages {
        stage('Test') {
            steps {
                sh "mkdir ${params.ID}"
            }
        }
    }
}
