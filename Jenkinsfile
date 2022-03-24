pipeline {
    agent any
    environment{
        AWS_DEFAULT_REGION = "us-east-1"
    }
    stages {
        stage('Submit Stack') {
            steps {
                 withCredentials([[
    $class: 'AmazonWebServicesCredentialsBinding',
    credentialsId: "ravi-demo-credentials",
    accessKeyVariable: 'AWS_ACCESS_KEY_ID',
    secretKeyVariable: 'AWS_SECRET_ACCESS_KEY'
]]) {
    // AWS Code
                     echo "hello"
}
            }}}}
