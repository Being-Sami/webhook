pipeline {
    agent any

    triggers {
        githubPush()
    }

    stages {
        stage('Hello') {
            steps {
                echo 'Hello Jenkins'
                eecho 'this is demo webhook' > fi.txt
            }
        }

        stage('Create Folder') {
            steps {
                sh 'mkdir -p devops'
            }
        }
    }
}
