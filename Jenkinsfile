pipeline {
    agent { label 'sameer' }
    stages {
        stage('Build') {
            steps {
                echo 'Buildingczc...'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                sh 'mvn package'
            }
        }
    }
}

