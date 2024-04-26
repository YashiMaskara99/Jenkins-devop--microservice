pipeline {
    //  agent any 
    agent {
        docker {
            image '3.9.6-eclipse-temurin-11'
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

