pipeline {
    agent {
        docker { image 'compulim/msbuild' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'dotnet --version'
            }
        }
    }
} 
