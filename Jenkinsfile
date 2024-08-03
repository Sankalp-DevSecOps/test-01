pipeline{
    agent any

    stages{
        stage('Clone Repo'){
            steps{
                git branch: 'main', credentialsId: '65ddbfc4-9f86-4090-8b78-4ffe84b097c5', url: 'https://github.com/Sankalp-DevSecOps/test-01.git'
            }
        }
    }
}
