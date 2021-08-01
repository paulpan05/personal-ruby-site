pipeline {
    agent {
      docker {
        image 'ruby'
        args '-u root'
      }
    }
    stages {
        stage('build') {
            steps {
                sh 'ruby --version'
            }
        }
    }
}