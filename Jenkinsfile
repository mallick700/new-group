pipeline {
    agent any

    stages {
        stage('Docker com') {
            steps {
               sh 'sudo chmod +x /usr/local/bin/docker-compose'
              sh 'docker-compose up -d'
            }
        }
    }
}
