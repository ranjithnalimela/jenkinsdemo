pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('uptime') {
            steps {
                sh 'uptime'
            }
        }
        stage('sleep') {
            steps {
                sleep 15
            }
        }
    }
}
