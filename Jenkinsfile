pipeline {
    agent { docker 'maven:3.8.9' }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}