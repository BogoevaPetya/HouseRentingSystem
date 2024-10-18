pipeline {
    agent any
    stages {
        stage('Build project') {
            steps {
                sh 'dotnet build'
            }
        }
        stage('Execute Tests') {
            steps {
                sh 'dotnet test'
            }
        }   
    }
}
