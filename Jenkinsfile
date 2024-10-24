pipeline {
    agent any

    stages {
        stage('Test') {
            steps {
                echo 'This is a simple test stage.'
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
