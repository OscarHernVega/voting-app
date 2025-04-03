pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/OscarHernVega/voting-app.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Compilando el proyecto...'
            }
        }
    }
}
