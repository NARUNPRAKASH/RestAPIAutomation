pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                sh '''
                cd APIAutoMation
                ls
                /usr/local/share/dotnet/dotnet build *.csproj
                '''
            }
        }

        stage('Test') {
            steps {
                sh '''
                cd APIAutoMation
                /usr/local/share/dotnet/dotnet test *.csproj
                '''
            }
        }

    }
}