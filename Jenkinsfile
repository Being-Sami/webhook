pipeline {
    agent any

    triggers {
        githubPush()
    }

    stages {

        stage('Create Folder') {
            steps {
                sh 'mkdir -p devops'
            }
        }

        stage('Hello') {
            steps {
                echo 'Hello Jenkins this is demo'
                sh 'echo "this pipeline is webhook" >> devops/f1.txt'
            }
        }
    }
}

