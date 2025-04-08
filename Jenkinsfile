pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('display sapid') {
            steps {
                sh 'echo "500105015"'
            }
        }
        stage('display batch') {
            steps {
                sh 'echo "3"'
            }
        }
    }
}
