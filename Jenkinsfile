pipeline {
     agent any
    //agent {
    //    docker {image 'node:19.6.0'}
    //}
 
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
