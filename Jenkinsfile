pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                dir('source') {
                    git branch: 'develop', url: 'https://github.com/your-repo.git'
                }
            }
        }
        stage('Build') {
            steps {
                echo 'Build steps go here...'
            }
        }
    }
}
