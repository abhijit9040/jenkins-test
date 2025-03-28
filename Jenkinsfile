pipeline{
    agent any
    stages{
        stage('checkout'){
            steps{
                git url: 'https://github.com/abhijit9040/Test2', branch: 'master'
                echo 'checkout completed'
                
            }
        }
        stage('build'){
            steps{
                echo 'build completed'
            }
        }
         stage('test'){
            steps{
                echo 'test completed'
            }
        }
         stage('deploy'){
            steps{
                echo 'deploy completed'
            }
        }
    }
}
