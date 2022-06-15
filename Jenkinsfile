
pipeline {

    agent any

    options {
        disableConcurrentBuilds()
    }

    stages {
        stage('install') {
            steps {
                sh 'echo "installing" > install-text.txt'
                sh 'echo "DOTENV_FILE = \'environments/local.env\'" > local_settings.py'
            }
        }
        stage('build') {
            steps {
                sh 'cat install-text.txt'
                sh 'cat local_settings.py'
            }
        }

    }
}

