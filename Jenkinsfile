pipeline{
    agent any
    stages{
        stage("Create zip file"){
            steps{
                zip middlewareScript-${BUILD_NUMBER}.zip * --exclude Jenkinsfile 
            }
        }
    }
}