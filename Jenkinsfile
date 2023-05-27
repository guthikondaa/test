pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                // Add your build steps here
                sh 'echo "mvn clean install"'
            }
        }
        
        stage('Test') {
            steps {
                // Add your test steps here
                sh 'echo "mvn test"'
            }
        }
        
        stage('Deploy') {
            steps {
                // Add your deployment steps here
                sh 'echo "mvn deploy"'
            }
        }
    }
}
