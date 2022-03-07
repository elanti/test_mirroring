pipeline {
    agent any

    triggers {
        pollSCM('*/2 * * * *')
    }

    stages {
        stage('Build doc') {
            steps {
                sh 'echo "Build doc"'
            }
        }

        stage('Upload doc') {
            steps {
                sh 'echo "Upload doc"'
            }
        }
    }
}
