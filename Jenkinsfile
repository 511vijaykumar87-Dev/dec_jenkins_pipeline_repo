pipeline{
    agent any
    stages{
        stage('STAGE1') {
            steps{
                echo "This is stage 12"
                sh '''
                    sleep 10
                    echo "this is linux command"
                    '''
                 }
            }
        stage('Build') {
            steps {
                echo "Building java code"
                sh '''#!/bin/bash
                      sleep 10
                      '''
            }
        }
    }
}
