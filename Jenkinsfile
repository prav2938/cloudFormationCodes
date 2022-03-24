pipeline {
    agent any
    environment{
        AWS_DEFAULT_REGION = "us-east-1"
    }
    stages {
        stage('Submit Stack') {
            steps {
                 withAWS(credentials: 'ravi-demo-credentials', region: 'us-west-2'){
    // some block

            sh "aws --version "
            }
            }}}}
