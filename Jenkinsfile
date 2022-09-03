pipeline {
    agent any

    stages {
        stage('Validate') {
            steps {
                sh 'mvn compile'
            }
        }
           stage('Unit Testing') {
            steps {
                sh 'mvn test'
            }
        }
          
    }
}

