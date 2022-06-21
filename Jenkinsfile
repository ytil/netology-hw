pipeline {
    agent {
        label "linux"
    }


    stages {
        stage('checkout') {
            steps {
                git credentialsId: 'e34ed197-6325-47a9-ad34-42be86415077', url: 'git@github.com:ytil/netology-hw.git'
            }
        }

        stage('molecule test') {
            steps {
                sh 'molecule test'
            }
        }
    }
}
