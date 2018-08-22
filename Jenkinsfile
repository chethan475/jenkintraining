pipeline {
    agent any
    stages {
        stage('compile stage') {

            steps {
               maven '3.5.0'
                sh 'mvn clean compile'
            }
        }
        stage('Test stage') {
            steps {
                 maven '3.5.0'
                sh 'mvn test'
            }
        }
    }
}

