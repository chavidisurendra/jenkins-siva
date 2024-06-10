pipeline{
    agent any
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