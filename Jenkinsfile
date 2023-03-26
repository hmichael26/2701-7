properties([pipelineTriggers([pollSCM('* * * * *')])])
pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('show files') {
            steps {
                bat 'dir'
            }
        }
    }
}
