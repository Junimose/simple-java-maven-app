pipeline {
    agent any
    tools {
        maven 'Maven'
                jdk 'JDK21' 
    }
    stages {
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
    }
}
