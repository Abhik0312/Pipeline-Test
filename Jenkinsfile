pipeline {
    agent any

    stages {
        stage('Pull Docker Image') {
            steps {
                script {
                    sh 'docker pull abhik1203/app:latest'
                }
            }
        }

        stage('Run Docker Container') {
            steps {
                script {
                    // Run the container and print the output
                    sh 'docker run --rm abhik1203/app'
                }
            }
        }
    }
}
