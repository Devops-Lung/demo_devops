pipeline {
    // agent any
    agent {
        docker {image 'node:16.3.1'}
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
