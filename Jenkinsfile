pipeline {
    agent any
    stages{
        stage('Build'){
            steps{
                bat 'localmaven clean package'
            }
        }
    }
}