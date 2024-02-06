pipeline {
    agent any

    stages {
        stage('Test') {
            
            steps {
                echo "Hello"
            }
        }
    }
	
	stages {
        stage('Test') {
            when {
                branch 'test'
            }
            steps {
                sh ''' cat Readme.md'''
            }
        }

    }
	
	
	
}