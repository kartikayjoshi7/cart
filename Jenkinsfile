pipeline {
    agent {
        label1 'WORKSTATION'
    }

    triggers {
        pollSCM('*/2 * * * *')
        }

    stages('Compile the code') {
        steps {
            sh 'compile code'
        }
    }
    stages('Check the code quality') {
            steps {
                sh 'check the code quality'
            }
        }
    stages('Test cases') {
            steps {
                sh 'Test cases'
            }
        }
}