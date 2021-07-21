pipeline {
    
    agent any
    
   stages {
        
        stage('Compile'){
            steps{
            bat 'mvn compile'
            }
          }
        stage('Test'){
            steps{
            bat 'mvntest'
            }
        }
        stage('Build'){
            steps{
            bat 'mvn install'
            }
        }
        stage('Deploy'){
            steps{
            bat 'mvn deploy'
            }
        }
   }
}
