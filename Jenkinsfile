pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/RivaldoRichsensa/aldo-repo.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building...'
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

    post {
        success {
            echo 'Pipeline sukses!'
        }
        failure {
            echo 'Pipeline gagal!'
        }
    }
}
