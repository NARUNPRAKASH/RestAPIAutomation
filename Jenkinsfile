pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                sh 'dotnet build RestApiAutomation.sln'
            }
        }

        stage('Test') {
            steps {
                sh 'dotnet test RestApiAutomation.sln'
            }
        }

    }
}