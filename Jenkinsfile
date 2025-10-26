pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/Megha-Malik/new-repo-jenkins.git'
            }
        }
        stage('Build') {
            steps {
                sh 'echo "Building project..."'
            }
        }
        stage('Test') {
            steps {
                sh 'echo "Running tests..."'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
    }
}
