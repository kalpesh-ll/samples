pipeline {
    agent any
    
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
            {
        stage('deploy') { 
            steps {
                sh 'node .' 
            }
        }
    }
}
