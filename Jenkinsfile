pipeline {
    agent any // where to execute
    stages {
        stage('Build') {
            steps {
                bat 'python fact.py'
            }
        }
    }
}
