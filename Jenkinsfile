pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/RivaldoRichsensa/Implementasi-Continuous-Integration-CI.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Build proses berjalan...'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing proses berjalan...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploy simulasi berhasil...'
            }
        }
    }
}
