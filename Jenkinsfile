pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
               echo "This is a minimal pipeline"
               sh 'javac /var/lib/jenkins/workspace/pipeline-main/src/TestingPipeline.java'
            }
        }
        stage('Here We can Run Julies Algorithm') {
            steps {
               echo "This is a minimal pipeline"
               sh 'ls -l'
            }
       }

               stage('This is Nurlan Branch') {
                   steps {
                      echo "This is a minimal pipeline"
                      sh 'ls -l'
                   }
              }


       stage('Finish Validation') {
                  steps {
                     echo "This is a minimal pipeline"
                  }
             }
     }
}