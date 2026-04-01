pipeline{
    agent any
    stages{
        stage{
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