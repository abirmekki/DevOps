
pipeline {
    agent any
    stages {
        stage ('Hello') {
            steps {
                echo 'Hello Abir'
            }
        }
        stage ('Git') {
            steps {
                echo 'Pulling...'
                    git branch : 'main',
                    url : 'https://github.com/abirmekki/git-test'
            }
        }
        stage ('Maven') {
            steps {
                sh "mvn -version"

            }
        }
    }
}
