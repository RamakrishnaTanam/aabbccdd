pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                git branch: 'main', url: 'https://github.com/RamakrishnaTanam/aabbccdd.git'

            }
        }
        stage('Build') {
            steps {
                sh 'javac hello.java'
            }
        }
        stage('Run') {
            steps {
                sh 'java hello'
            }
        }
    }
}

