pipeline {
    agent any

    stages {

        stage('Clone') {
            steps {
                git url: 'https://github.com/Maaz-ismail-md/jenkins-simple-demo.git', branch: 'main'
            }
        }

        stage('Run Script') {
            steps {
                sh 'chmod +x script.sh'
                sh './script.sh'
            }
        }

        stage('Run Python File') {
            steps {
                sh 'python3 ngrok.py'
            }
        }
        stage('Run Python File') {
            steps {
                sh 'python3 ngrok1.py'
            }
        }
        stage('Run Python File') {
            steps {
                sh 'chmod +x add.py'
                sh 'python3 add.py'
            }
        }
        stage('Run Python1 File') {
            steps {
                sh 'python3 print.py'
            }
        }
        stage('Run Python7 File') {
            steps {
                sh 'chmod +x add2.py'
                sh 'python3 add2.py'
            }
        }

    }
}
