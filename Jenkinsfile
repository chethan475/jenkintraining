pipeline {
    agent any
    stages {
        stage('compile stage') {

            steps {
              withMaven (maven: 'M3')
                echo 'tst'
                sh 'mvn clean install'
                echo 'tst1'
            }
        }
        stage('Test stage') {
            steps {
               withMaven (maven: 'M3')
                sh 'mvn test'
            }
        }
    }
}

