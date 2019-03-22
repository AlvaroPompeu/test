pipeline {
    agent any
    triggers {
	pollSCM '0 * * * *'
    }
    stages {
        stage('Test') {
            steps {
                sh './scropt.sh'
            }
        }
    }
}
