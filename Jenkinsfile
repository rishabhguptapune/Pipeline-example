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
}