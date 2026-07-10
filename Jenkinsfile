pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Production Build"
            }
        }

        stage('Approval') {
            steps {
                input "Deploy to Production?"
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying to Production"
            }
        }
    }
}