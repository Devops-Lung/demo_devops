pipeline {
    // agent any
    agent {
        docker {image 'node:lts-alpine3.17'}
    }
 
    stages {
        stage('build code') {
            steps {
                sh '''
                npm install
                npm run build
                '''
            }
        }
    }
}
