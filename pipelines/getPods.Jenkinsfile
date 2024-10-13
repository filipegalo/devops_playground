pipeline {
    agent any
    stages {
        stage('Run kubectl get pods') {
            steps {
                sh 'kubectl get pods'
            }
        }
    }
}
