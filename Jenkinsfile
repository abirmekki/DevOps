
pipeline {
    agent any

    stages {
        stage('Récupération du code source depuis Git') {
            steps {
               git 'https://github.com/abirmekki/DevOps'
                }
        }

        stage('Affichage de la date système') {
            steps {
                sh 'date'
            }
        }
    }
}
