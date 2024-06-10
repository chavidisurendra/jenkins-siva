pipeline{
    agent{
        label 'Agent-1'
    }
    options{
        timeout( time: 5, unit: 'Minutes')
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