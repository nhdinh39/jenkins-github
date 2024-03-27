pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                git branch: 'main', url: 'https://github.com/nhdinh39/jenkins-github.git'
            }
        }
    }
}