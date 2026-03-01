pipeline {
    agent any

    stages {
        stage('Lab Requirements') {
            steps {
                // This displays the Public IP of your Jenkins server
                echo "The JENKINS_URL is: ${env.JENKINS_URL}"
                
                // This displays the specific ID of this automated build
                echo "The BUILD_ID is: ${env.BUILD_ID}"
            }
        }
    }
}
