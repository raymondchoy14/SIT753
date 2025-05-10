pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Installing dependencies...'
                sh 'echo "Simulated: npm install"'
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo 'Running unit and integration tests...'
                sh 'echo "Simulated: npm test"'
            }
        }

        stage('Code Analysis') {
            steps {
                echo 'Running code analysis...'
                sh 'echo "Simulated: npx eslint"'
            }
        }

        stage('Security Scan') {
            steps {
                echo 'Checking for security vulnerabilities...'
                sh 'echo "Simulated: npm audit"'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Deploying to staging environment...'
                sh 'echo "Simulated: deploy to staging"'
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo 'Running integration tests on staging...'
                sh 'echo "Simulated: tests passed on staging"'
            }
        }

        stage('Deploy to Productions') {
            steps {
                echo 'Deploying to production environment...'
                sh 'echo "Simulated: deploy to production"'
            }
        }
    }
}
