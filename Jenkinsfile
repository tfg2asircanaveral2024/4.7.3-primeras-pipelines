pipeline {
    agent any

    stages {
        stage('Primera fase') {
            steps {
                // comprobar si hay contenido en el Workspace
                sh 'ls'
                sh 'echo "Un archivo nuevo" > archivo.txt'
            }
        }

        stage('Segunda fase') {
            steps {
                sh 'ls'
                sh 'cat archivo.txt'
            }
        }
    }
}