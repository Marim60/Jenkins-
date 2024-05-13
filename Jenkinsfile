pipeline {
    agent any
    stages {
        stage('Execute Bash Script') {
            steps {
     git credentialsId: 'https://github.com/Marim60/Jenkins-.git'

                sh './execute_is_command.sh'
            }
        }
    }
}
