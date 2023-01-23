pipeline{
    agent any
    stages{
        stage("Create zip file"){
            steps{
                sh 'zip middlewareScript-${BUILD_NUMBER}.zip * --exclude Jenkinsfile' 
            }
        }
    }
}