pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Adding trigger for build stage"
                echo "Building from Jenkinsfile in GitHub..."
                sh '''
                    echo "doing build stuff..."
                    sleep 1
                '''
            }
        }

        stage('Test') {
            steps {
                echo "Testing..."
                sh '''
                    echo "doing test stuff..."
                    sleep 1
                '''
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying..."
                sh '''
                    echo "doing deploy stuff..."
                    sleep 1
                '''
            }
        }
    }
}
