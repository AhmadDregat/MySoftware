properties([pipelineTriggers([pollSCM('30 * * * *')])])
pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh 'ls'
                sh 'python3 Welcome.py'
                sh 'python3 Click.py'
            }
        }
    }
}
