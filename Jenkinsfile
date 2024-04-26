pipeline {
    //  agent any 
    agent {
        docker {
            image 'node:20.11.1-alpine3.19'
        }
    }
    stages {
        stage('Build'){
            steps {
        echo "image build"
        // sh 'mvn --version'
        }
        }
    
    
        stage('Test'){
            steps {
        echo "Test"
            }
        }
    
    
        stage('Integration test'){
            steps {
        echo "Integration test"
            }
        }
    }
        
}

