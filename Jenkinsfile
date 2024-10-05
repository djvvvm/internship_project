pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git branch: 'develop', url: 'https://github.com/djvvvm/internship_project.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
    }
}
