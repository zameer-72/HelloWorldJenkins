pipeline {
     agent any
    stages {
        stage('build') {
            steps {
                sh 'javac *.java'
                sh 'java Hello'
            }
        }
    }
}

