pipeline {
    agent any

    stages {
        stage('Test') {
            
            steps {
                echo "Hello"
            }
        }
		
		stage('Test2') {
            when {
                branch 'test'
            }
            steps {
                sh ''' cat Readme.md'''
            }
        }
    }
	
	
	
}