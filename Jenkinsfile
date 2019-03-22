pipeline {
    agent any
    triggers {
	pollSCM 'H/2 * * * *'
    }
    stages {
        stage('Test') {
            steps {
                sh './scropt.sh'
            }
        }
    }
}
