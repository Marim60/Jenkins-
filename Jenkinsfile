pipeline {
    agent {
        label 'windows' // Specify a label for a Windows agent
    }
    stages {
        stage('Checkout') {
            steps {
                git credentialsId: 'Pipeline_Jenkins', url: 'https://github.com/Marim60/Jenkins-.git'
            }
        }
        stage('Execute Bash Script') {
            steps {
               bat 'execute_ls_command.bat'
            }
        }
    }
}
