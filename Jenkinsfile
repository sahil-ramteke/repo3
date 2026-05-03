pipeline {
    agent any

    stages {
        stage('Clone Repo') {
            steps {
               git branch: 'main', url: 'https://github.com/sahil-ramteke/repo3'
            }
        }

        stage('Copy File') {
            steps {
                sh 'cp index.html /var/www/html'
            }
        }
    }
}
