pipeline {
    agent any
    stages {
        stage('Execute Bash Script') {
            steps {
                script {
                    sh '''
                    ls -l
                    echo "Executing script..."
                    ./execute_ls_command.sh
                    '''
                }
            }
        }
    }
}
