pipeline {

    agent any
    stages {

        stage("complile") {

            steps {
                sh 'javac test.java'
            }

        }

        stage("run") {

           steps {
             sh 'java test'
           }
        }   
        
        }

        post {

            always {
                sh 'echo "Always"'
            }

            success {
                sh 'echo "Success"'
            }

            failure {
                sh 'echo "Failure"'
            }
        }
}