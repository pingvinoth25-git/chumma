pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                sh 'echo "Build successful"'
            }
        }

        stage('Deploy') {
            steps {
                sh 'cp index.html /var/www/html/'
            }
        }

    }
}
