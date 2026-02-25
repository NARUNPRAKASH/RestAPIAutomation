pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                sh 'cd APIAutoMation && /usr/local/share/dotnet/dotnet build APIAutoMation.csproj'
            }
        }

        stage('Test') {
            steps {
                sh 'cd APIAutoMation && /usr/local/share/dotnet/dotnet test APIAutoMation.csproj'
            }
        }

    }
}