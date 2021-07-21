pipeline {
    agent any
   
    stages {

        stage('Test'){
            steps{
            sh 'mvn3 test'
            }
        }
        stage('Build'){
            steps{
            sh 'mvn3 install'
            }
        }
        stage('Deploy'){
            steps{
            sh 'mvn3 deploy'
            }
        }
   }
}
