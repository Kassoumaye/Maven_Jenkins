pipeline {
   agent { label 'Serveur_Client_Jenkins' }
    stages {
        stage('build') {
            steps {
               git branch: 'main', credentialsId: '3ecf86bd-a977-4b64-a0a2-a87d12f3031d', url: 'https://github.com/Kassoumaye/Maven_Jenkins.git'
            }
        }
    }
}
