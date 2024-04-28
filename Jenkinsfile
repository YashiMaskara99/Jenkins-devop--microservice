// pipeline {
//      agent any 
   
//     stages {
//         stage('Build'){
//             steps {
//         echo "build"
//         }
//         }
    
    
//         stage('Test'){
//             steps {
//         echo "Test"
//             }
//         }
    
    
//         stage('Integration test'){
//             steps {
//         echo "Integration test"
//             }
//         }
//     }
        
// }
pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                // Build your application here
                  echo "build"
            }
        }
        stage('Deploy') {
            steps {
                // Deploy your application here
                sh 'kubectl apply -f deployment.yml'
            }
        }
    }
    
    post {
        success {
            echo 'Deployment successful!'
            // Send notification or trigger downstream jobs
        }
        failure {
            echo 'Deployment failed!'
            // Send notification or take remedial actions
        }
    }
}


