pipeline {
    agent any

    stages {
        
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
             stage('Mani') {
            steps {
                echo 'Manikanta'
            }
             }
              stage('Environment') {
            steps {
                echo env.BUILD__ID
                echo env.JENKINS_HOME
                echo env.JOB_NAME
            }
        }
    }
}

