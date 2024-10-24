pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                npm install
                npm start
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                npm run test
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
    }
}
