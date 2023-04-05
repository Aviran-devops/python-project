properties([pipelineTriggers([pollSCM('* 8 * * *')])])
pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('heloo poll scm') {
            steps {
                echo 'heloo poll scm'
            }
        }
        stage('run python') {
            steps {
               python python\-project/main.py
            }
        }
    }
}
