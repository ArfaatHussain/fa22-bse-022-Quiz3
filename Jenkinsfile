pipeline {
    agent any

    stages {
        stage('Compile Java') {
            steps {
                bat 'javac Main.java'
            }
        }

        stage('Run Java Program') {
            steps {
                bat 'java Main'
            }
        }
    }
}
