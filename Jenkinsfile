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
            	app = docker.build("nginx/hellonode") 
            }
        }
    }
}
