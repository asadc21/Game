pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                // To run Maven on a Windows agent, use
                bat "mvn clean package"
            }
        }
        stage('Test') {
            steps {
                // To run Maven on a Windows agent, use
                bat "mvn test"
            }
        }
        stage('Deploy') {
            steps {
                // To run Maven on a Windows agent, use
                bat "mvn deploy"
            }
        }
        stage('Clean') {
            steps {
                // To run Maven on a Windows agent, use
                bat "mvn clean package"
            }
        }
    }
}
