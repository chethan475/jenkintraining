pipeline {
    agent any
    stages {
        stage('compile stage') {

            steps {
              withMaven (maven: 'M3')
               sh 'echo "path: ${PATH}"'
                
          
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

