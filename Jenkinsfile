pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Running Java Program"
                sh 'javac Main.java'
                sh 'java Main'
            }
        }
    }
}
