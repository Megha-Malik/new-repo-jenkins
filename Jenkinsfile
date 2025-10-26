pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git branch:'main',
                    credentialsId: 'GITHUB',
                    url: 'https://github.com/Megha-Malik/new-repo-jenkins.git'
            }
        }
        stage('Build') {
            steps {
                sh 'echo "Building project..."'
                sh 'ls -l'
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
