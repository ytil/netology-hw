pipeline {
    agent {
        label "linux"
    }


    stages {
        stage('molecule test') {
            steps {
                sh 'molecule test'
            }
        }
    }
}
