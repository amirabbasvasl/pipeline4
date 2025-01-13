pipeline {
    agent any

    stages {
        stage('first') {
            steps {
                echo 'Hello World'
            }
        }
        stage('second') {
            steps {
            	sh 'app = docker.build("nginx/hellonode")'
            }
        }
    }
}
