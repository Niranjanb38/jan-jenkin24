pipeline {
    agent none
        environment{
            TEST = "test_variable"
            TEST1 = "test_variable1"
        }
    stages {
         stage('Build') {
            agent {
                label 'slave1' 
        }
            steps {
                 sh '''
                    echo $TEST $TEST1
                    sleep 5
                    '''
                
            }
            
    }
        stage ('test') {
        agent any
            steps {
                 sh '''
                    #!/bin/bash
                    ls -lrt
                    echo $TEST $TEST1
                    sleep 5
                    '''
                }
             }
    }
}