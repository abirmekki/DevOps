
pipeline {
    agent any
    stages {
        stage ('Hello') {
            steps {
                echo 'Hello abir'
            }
        }
        stage ('Hello') {
            steps {
                echo 'Pulling...'
                    git branch : 'main',
                    url : https://github.com/abirmekki/DevOps'
            }
        }
        stage ('Testing Maven') {
            steps {
                sh "mvn-version"

            }
        }
    }
}