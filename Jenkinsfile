pipeline {
    agent any
    triggers {
	pollSCM '* * * * *'
    }
    stages {
        stage('Test') {
            steps {
                sh './scropt.sh'
            }
        }
    }
}
