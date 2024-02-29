pipeline {
    agent any

    stage{
        stage ('build'){
            steps{
                sh 'sleep 5'
                
            }
            
        }
        
    }
    stage{
        stage ('test'){
            steps{
                sh '''
                    #!/bin/bash
                    ls -lrt
                    sleep 5
                    '''
            }
            
        }
        
    }
}