pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
			sh './hello.sh'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
    }
}
