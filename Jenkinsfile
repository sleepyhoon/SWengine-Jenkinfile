pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                build 'PipeLineJob1'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
