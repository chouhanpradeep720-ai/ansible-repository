pipeline{
    agent any
    stages{
        stage('ssh agent'){
            steps{
                script{
                    sshagent(['ansible-server-key']) {
                        sh 'ls -la'
                    }
                }
            }
        }
    }
}