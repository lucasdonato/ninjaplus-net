pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                echo 'instalando dependências..'
                //sh "npm install"
            }
            
        }
        stage('Tests') {
            steps {
                sh "dotnet test"
            }
        }
    }
}