pipeline {
    // agent any
    agent {
        docker {image 'node'}
    }
 
    stages {
        stage('Build Code') {
            steps {
                sh '''
                npm install
                npm run build
                '''
            }
        }
    }
}
