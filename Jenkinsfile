pipeline{
    agent{
        label 'Agent-1'
    }
    stages{
        stage('build'){
            steps{
               sh 'build'
            }
        }
        stage('test'){
            steps{
                sh 'test'
            }
        }
        stage('deploy'){
            steps{
              sh 'deploy'
            }
        }
    }
}