pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                // Add your build logic here, e.g., running a Maven build
                // sh 'mvn clean package'
            }
        }
        
        stage('Test') {
            steps {
                echo 'Testing...'
                // Add your testing logic here, e.g., running unit tests
                // sh 'mvn test'
            }
        }
        
        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Add your deploy logic here
                // sh 'scp target/my-app.war user@server:/path/to/deploy'
            }
        }
    }
    
    post {
        success {
            echo 'Pipeline succeeded!'
        }
        failure {
            echo 'Pipeline failed!'
        }
    }
}
