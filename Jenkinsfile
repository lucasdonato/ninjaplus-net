pipeline {
     agent {
        docker { 
            image "mcr.microsoft.com/dotnet/core/sdk:3.1.100-alpine3.10"
            args "--network=skynet"
        }
    }
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