pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'javac helloworld.java'
            }
        }
        stage('Run') {
            steps {
                sh 'java helloworld'
            }
        }
    }
}