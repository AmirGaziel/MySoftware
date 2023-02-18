
pipeline {
    agent any

    stages {
        stage('Click') {
            steps {
                sh 'python3 Click.py'
            }
        }
        stage('NewScreen') {
            steps {
                sh 'python3 NewScreen.py'
            }
        }

    }
}


