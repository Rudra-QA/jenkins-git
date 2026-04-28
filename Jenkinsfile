pipeline {
    agent any

    stages {

        stage('Checkout Code') {
            steps {
                echo "Getting latest code from GitHub"
                git 'https://github.com/Rudra-QA/jenkins-demo.git'
            }
        }

        stage('Run App') {
            steps {
                sh 'python3 app.py'
            }
        }
    }
}
