
pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'mvn clean install'
            }
        }
        stage('Test') {
            steps {
                echo 'mvn test'
            }
        }
        stage('Deploy') {
            steps {
                echo 'mvn deploy'
            }
        }
    }
}

