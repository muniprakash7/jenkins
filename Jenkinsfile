pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Getting project files from GitHub...'
                git 'https://github.com/muniprakash7/car-website.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building the car website project...'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing the car website project...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying the car website project...'
            }
        }
    }

    post {
        success {
            echo 'Car website pipeline completed successfully!'
        }
        failure {
            echo 'Car website pipeline failed!'
        }
    }
}
