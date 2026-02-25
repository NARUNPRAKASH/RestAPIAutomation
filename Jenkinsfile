pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                sh '/usr/local/share/dotnet/dotnet build RestApiAutomation.sln'
            }
        }

        stage('Test') {
            steps {
                sh '/usr/local/share/dotnet/dotnet test RestApiAutomation.sln'
            }
        }

    }
}