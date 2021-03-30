pipeline {
    agent any
    tools {
        maven 'Maven 3.6.3'
        jdk 'JDK 16'
    }

    stages {
        stage('Build') {
            steps {
                echo 'Hello World'
                sh 'java --version'
                sh 'mvn clean compile'
            }
        }

    }
}