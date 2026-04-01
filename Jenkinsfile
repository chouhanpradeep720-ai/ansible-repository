pipeline{
    agent any
    stages{
        stage('ssh agent'){
            steps{
                script{
                    sshagent(['ansible-key']) {
                        sh 'ls -la'
                    }
                }
            }
        }
    }
}