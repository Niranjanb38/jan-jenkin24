pipeline {
    agent {
        lebel 'slave1'
    }

    stages {
        stage ('Build') {
            steps {
                 sh 'sleep 5'
                
            }
            
        }
        stage ('Build1') {
            steps {
                 sh 'sleep 10'
                
            }
            
        }
        

        stage('Test') {
            steps {
                sh '''
                    #!/bin/bash
                    ls -lrt
                    sleep 10
                '''
            }
        }   
        stage('Test1') {
            steps {
                sh '''
                    #!/bin/bash
                    pwd
                    sleep 5
                '''
            }
        }   
    }
        

}