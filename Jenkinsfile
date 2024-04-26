pipeline {
    //  agent any 
    agent {
        docker {
            image 'maven'
        }
    }
    stages {
        stage('Build'){
            steps {
        echo "mvn --version"
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

