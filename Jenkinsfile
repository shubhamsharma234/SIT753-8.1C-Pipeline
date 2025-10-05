pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building the application...'
            }
        }
        stage('Unit and Integration Tests') {
            steps {
                echo 'Running tests...'
            }
        }
        stage('Code Analysis') {
            steps {
                echo 'Analyzing code quality...'
            }
        }
        stage('Security Scan') {
            steps {
                echo 'Performing security scan...'
            }
        }
        stage('Deploy to Staging') {
            steps {
                echo 'Deploying to staging environment...'
            }
        }
        stage('Integration Tests on Staging') {
            steps {
                echo 'Running integration tests on staging...'
            }
        }
        stage('Deploy to Production') {
            steps {
                echo 'Deploying to production...'
            }
        }
    }
    post {
        success {
            echo 'Pipeline executed successfully for Shubham Sharma!'
        }
        failure {
            echo 'Pipeline failed. Please check the console output.'
        }
    }
}
