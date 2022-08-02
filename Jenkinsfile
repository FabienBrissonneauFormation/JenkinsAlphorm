pipeline {
    agent any
    stages {
        stage('Build'){
            steps {
                echo 'Build en cours ...'
                sh 'ecrire.sh'
            }
        }
        stage('Test'){
            steps {
                echo 'Test en cours ...'
            }
        }
        stage('Release'){
            steps {
                echo 'Release en cours ...'
            }
        }
        stage('Deploy'){
            steps {
                echo 'Deploy en cours ...'
            }
        }
    }
}
