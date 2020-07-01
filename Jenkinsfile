pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo  "first demo in python"
                sh  '''pwd
                       python3 demo.py
                    '''
            }
        }
        stage('Test') {
            steps {
                echo 'Testing my first demo..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying my first demo....'
            }
        }
    }
}
