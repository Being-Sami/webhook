pipeline {
    agent any

    triggers {
        githubPush()
    }

    stages {
        stage('Hello') {
            steps {
                echo 'Hello Jenkins'
            }
        }

        stage('Create Folder') {
            steps {
                sh 'mkdir -p devops'
            }
        }
    }
}
