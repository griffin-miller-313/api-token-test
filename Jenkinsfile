pipeline {
    environment {
        JENKINS_API_TOKEN = credentials('jenkins_api_token')
    }
    stages {
        stage('Foo') {
            echo "JENKINS_API_TOKEN = ${env.JENKINS_API_TOKEN}"
        }
    }
}