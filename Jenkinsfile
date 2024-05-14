pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git credentialsId: 'Pipeline_Jenkins', url: 'https://github.com/Marim60/Jenkins-.git'
            }
        }
        stage('Execute Bash Script') {
            steps {
               powershell 'execute_is_command.ps1'
            }
        }
    }
}
