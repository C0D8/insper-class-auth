pipeline{
    agent any
    stages{
        stage('Jenkis Auth'){
            steps{
                echo 'Jankins auth interface'
            }
        }
        stage('Build'){
            steps{
                sh 'mvn clean install'
            }
        }
       
    }
}