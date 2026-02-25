pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                sh '/usr/local/share/dotnet/dotnet build APIAutoMation/APIAutoMation.csproj'
            }
        }

        stage('Test') {
            steps {
                sh '/usr/local/share/dotnet/dotnet test APIAutoMation/APIAutoMation.csproj'
            }
        }

    }
}