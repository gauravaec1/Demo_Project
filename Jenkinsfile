pipeline {
    agent any
    stages {
            stage('Build') {
            steps {
                echo 'Building the code..'
                git clone https://github.com/gauravaec1/Hello.git
            }
        }

        stage('Test') {
            steps {
                echo 'Testing the code'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the code'
            }
        }
    }
}
