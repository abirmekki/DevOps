
pipeline {
    agent any

    stages {
        stage('Récupération du code source depuis Git') {
            steps {
                script {
                echo 'Pulling...'
                git branch:'main',
                url:'https://github.com/abirmekki/DevOps'
                    checkout scm
                }
            }
        }

        stage('Affichage de la date système') {
            steps {
                sh 'date'
            }
        }
    }
}
