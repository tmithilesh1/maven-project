pipeline {
    agent any

    environment {
        VAR_NAME = "value"
    }

    parameters {
        string(name: 'ENV', defaultValue: 'dev', description: 'Deployment environment')
    }

    stages {
        stage('Stage Name') {
            steps {
                echo "Do something here"
                // sh 'your-shell-command'
            }
        }

        // Add more stages as needed
    }

    post {
        success {
            echo "Pipeline succeeded"
        }
        failure {
            echo "Pipeline failed"
        }
    }
}
