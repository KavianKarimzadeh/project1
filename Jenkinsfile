pipeline{
    agent {node{label 'slave1'}}
    stages{
        stage('Build'){
            steps{
                echo "Building"
            }
        }
        stage('Test'){
            steps{
                echo "Testing"
            }
        }
        stage('Deploy'){
            steps{
                echo "Deploying"
            }
        }
    }
    post{
        always{
            echo "Post action is run"
        }
    }
}
