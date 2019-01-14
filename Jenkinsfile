pipeline {
    agent { label 'slave'}
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
