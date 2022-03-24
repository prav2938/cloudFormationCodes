pipeline {
    agent any
    enviroment{
        AWS_DEFAULT_REGION = "us-east-1"
    }
    stages {
        stage('Submit Stack') {
            steps {
                withCredentials([[
    $class: 'AmazonWebServicesCredentialsBinding',
    credentialsId: "credentials-id-here",
    accessKeyVariable: 'AWS_ACCESS_KEY_ID',
    secretKeyVariable: 'AWS_SECRET_ACCESS_KEY'
]])
            sh "aws --version "
              }
             }
            }
            }
