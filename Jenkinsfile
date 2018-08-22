pipeline {
    agent none
    stages {
        stage('compile stage') {

            steps {
              withMaven (maven: 'M3')
               sh 'echo "path: ${PATH}"'
                sh 'mvn clean install'
          
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

