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
        stage('Deploy'){
            steps{
                echo 'Deploying...'
            }
        }
    }
}