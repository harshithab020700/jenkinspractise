pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                // Clone using credentials
                git branch: 'main',
                    credentialsId: '6170a535-e9b6-4d82-bd1b-17c00add5ffe', 
                    url: 'https://github.com/harshithab020700/jenkinspractise.git'
            }
        }

        stage('List Files') {
            steps {
                // Verify the repository is cloned
                sh 'ls -la'
            }
        }
    }
}
