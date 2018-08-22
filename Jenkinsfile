pipeline {
    agent none
    stages {
        stage('compile stage') {

            steps {
              maven 'Maven 3.5.0'
                sh 'mvn clean compile'
            }
        }
        stage('Test stage') {
            steps {
                 maven 'Maven 3.5.0'
                sh 'mvn test'
            }
        }
    }
}

