pipeline{
    agent any
    stages{
        stage('clone code'){
            steps{
                echo 'Hello dosto'
            }
        }
        stage('build'){
            steps{
                echo 'Build code'
            }
        }
        stage('test'){
            steps{
                    echo 'Test code'
                }
           
        }
        stage('deploy'){
            steps{
                echo 'Deploy code'
            }
        }
        stage{
            steps{
                echo 'smoke test'
            }
        }
    }
}