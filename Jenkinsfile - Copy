pipeline {
    agent any

    stages {
        stage('Test') {
            when {
                branch 'test'
            }
            steps {
                script {
                    build job: 'testing-test', wait: false
                }
            }
        }

        stage('Stage') {
            when {
                branch 'stage'
            }
            steps {
                script {
                    build job: 'testing-stage', wait: false
                }
            }
        }
    }
}