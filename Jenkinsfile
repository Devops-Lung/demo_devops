pipeline {
    // agent any
    agent {
        docker {image 'node'}
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
