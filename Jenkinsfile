pipeline{
    agent any
    stages{
        stage('Build'){
            steps{
                echo 'This is first project in Jenkins'
            }
        }
        stage('Docker build'){
            steps{
                echo 'Here I am building docker image'
            }
        }
        stage('Testing Jenkins POLL-SCM'){
            steps{
                echo 'Here I am Testing jenkins Poll SCM'
            }
        }
        stage('Testing webhook'){
            steps{
                echo 'Here I am Testing webhook and build are automatically triggered on service'
            }
        }
        stage('Deploy'){
            steps{
                echo 'Deploying...'
            }
        }
    }
}