pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                 sh sample.sh
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                sh sample.sh
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
                sh sample.sh
            }
        }
    }
}
