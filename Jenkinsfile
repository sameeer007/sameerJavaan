pipeline {
    agent { label 'sameer' }
    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                mvn package
                echo 'Deploying....'
            }
        }
    }
}

