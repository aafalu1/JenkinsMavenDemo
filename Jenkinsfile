pipeline {
    agent any
    tools {
        maven 'Apache Maven 3.9.1'
        jdk 'openjdk 11.0.18 2023-01-17 LTS'
    }
    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }
        stage('Build') {
            steps {
                bat 'mvn clean package'
            }
        }
        stage('Test') {
            steps {
                bat 'mvn test'
            }
        }
        stage('Deploy') {
            steps {
                bat 'mvn deploy'
            }
        }
    }
}
