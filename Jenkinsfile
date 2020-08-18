pipeline {
    agent { docker { image 'gradle:6.6.0-jdk11' } }
    stages {
        stage('build') {
            steps {
                sh 'java --version'
            }
        }
    }
}
