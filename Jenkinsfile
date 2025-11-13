pipeline {
    agent { docker 'maven:3.9.9-eclipse-temurin-17' }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}