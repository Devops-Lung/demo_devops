pipeline {
    // agent any
    agent {
        docker {image 'node:16.19.0'}
    }
 
    stages {
        stage('build code') {
            steps {
                sh '''
                sudo npm install
                sudo npm run build
                '''
            }
        }
    }
}
