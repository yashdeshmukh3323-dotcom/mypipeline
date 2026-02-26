pipeline {
    agent any

    stages {
        stage('Dev') {
            steps {
                echo 'I am in Dev'
                sh 'git --version'
                
            }
        }
 stage('Testing') {
            steps {
                echo 'I am in Testing'
                sh 'python3 --version'
            }
        }
 stage('Production') {
            steps {
                echo 'I am in Production'
                sh 'docker --version'
            }
        }
    }
}
pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps {
                git 'https://github.com/yashdeshmukh3323-dotcom/mypipeline.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Build stage'
            }
        }

        stage('Test') {
            steps {
                echo 'Test stage'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploy stage'
            }
        }
    }

    post {
        success {
            echo '✅ Pipeline'
        }
        failure {
            echo '❌ Pipeline'
        }
    }
}
