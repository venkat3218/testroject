pipeline {
    agent any 
    stages {
        stage('Checkout') {
            steps {
                .git'
            }
        }
            stage('Build'){
                steps{
                    sh label: '', script: 'mvn clean package'
                }
            }
        }
    
}
