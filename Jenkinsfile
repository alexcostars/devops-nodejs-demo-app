pipeline {
    agent any
    tools {nodejs "latest"}
    stages {
        stage('build') {
            steps {
                echo 'building the software'
                sh 'npm install'
            }
        }
        stage('test') {
            steps {
                echo 'testing the software'
                sh 'npm test'
            }
        }
    }
}

