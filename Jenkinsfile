pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                build 'SWengine-Jenkinfile'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
