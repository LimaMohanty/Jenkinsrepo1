pipeline {
    agent any
    
    stages {
        stage('Clone') {
            steps {
                // Clone the repository
                git url: 'https://github.com/LimaMohanty/Jenkinsrepo1.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building...'
                sh 'javac hello.java'
            }
        }
        stage('run') {
            steps {
                echo 'running...'
                sh 'java hello'
            }
        }
      
            }
        }
    
