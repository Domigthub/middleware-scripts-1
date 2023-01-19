pipeline {
    agent any

    stages{
        stage("create zip file"){
            steps{
               
           sh 'zip middleware-scripts-${BUILD_NUMBER}.zip *  --exclude Jenkinsfile README.md '  
            
            }
        }
        
    }
}