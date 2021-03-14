pipeline {
    agent any
    stages {
        stage ('inicio') {
            steps {
                bat 'echo Inicio'
            }
        }
        stage ('Meio') {
            steps {
                bat 'echo Meio'
                bat 'echo Meio de Novo'
            }
        }
        stage ('Fim') {
            steps {
                sleep(5)
                bat 'echo Fim'
            }
        }
    }
}