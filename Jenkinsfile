```groovy
pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Checking out source code from GitHub'
                checkout scm
            }
        }

        stage('Build') {
            steps {
                bat 'echo Building Application'
            }
        }

        stage('Test') {
            steps {
                bat 'echo Testing Application'
            }
        }

        stage('Docker Build') {
            steps {
                bat 'docker --version'
            }
        }

        stage('Deploy') {
            steps {
                bat 'echo Deployment Successful'
            }
        }
    }
}
```
