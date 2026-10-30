pipeline {
    agent any
    tools {
        maven 'Maven'
        jdk 'JDK21' 
    }
    stages {
        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }
        stage('Test') {
            steps {
                sh 'mvn test'
            }
        }
    }
}
