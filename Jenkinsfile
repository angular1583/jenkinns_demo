pipeline {
    agent any
    tools {nodejs "node"}
    stages {
        stage('build') {
            steps {
               sh 'npm start'
            }
        }
    }
}
