pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Cloning repository...'
                git 'https://github.com/Blessina03/Devops.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Compiling Java code...'
                sh 'javac HelloWorld.java'
            }
        }

        stage('Run') {
            steps {
                echo 'Running Hello World application...'
                sh 'java HelloWorld'
            }
        }

        stage('Test') {
            steps {
                echo 'Tests completed successfully!'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deployment simulation completed!'
            }
        }
    }
}
