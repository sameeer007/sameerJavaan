pipeline {
    agent { label 'sameer' }
    stages {
        stage('Build') {
            steps {
                echo 'Buildcing..'
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

