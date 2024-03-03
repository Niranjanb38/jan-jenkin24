pipeline {
    agent none

    stages {
         stage('Build') {
            agent {
                label 'slave1' 
        }
            steps {
                 sh 'sleep 5'
                
            }
            
    }
        stage ('test') {
        agent any
            steps {
                 sh 'sleep 10'
                }
             }
    }
}