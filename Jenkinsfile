pipeline {
    agent any
    options {
        timeout(time: 1, unit: 'HOURS')
    }
    stages {
        stage('copy repo') {
            steps {
                git branch: 'main', credentialsId: 'github_credentials', url: 'https://github.com/Koventhan28/iactesting.git'                
            }
        }
    }
}