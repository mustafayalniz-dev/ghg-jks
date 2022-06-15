
pipeline {
    stages {
        stage('install') {
            steps {
                sh 'echo "installing" > install-text.txt'
            }
        }
        stage('build') {
            steps {
                sh 'cat install-text.txt'
            }
        }

    }
}

