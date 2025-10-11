pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                bat 'dotnet build'
            }
        }
        stage('Run test') {
            steps {
                bat 'dotnet test'
            }
        }
    }
}

