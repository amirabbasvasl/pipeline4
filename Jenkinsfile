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
            	dockerImage('nginx/hellonode')
            }
        }
    }
}
