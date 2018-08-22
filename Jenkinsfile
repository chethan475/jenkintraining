pipeline {
    agent any
    stages {
        stage('compile stage') {

            steps {
               withMaven
                sh 'mvn clean compile'
            }
        }
        stage('Test stage') {
            steps {
                withMaven
                sh 'mvn test'
            }
        }
    }
}

