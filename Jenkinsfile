
pipeline {
    agent any

    stages {
        stage('Click') {
            steps {
                sh 'python3 Click.Py'
            }
        }
        stage('NewScreen') {
            steps {
                sh 'python3 welcome.py'
            }
        }

    }
}


