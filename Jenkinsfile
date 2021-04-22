pipeline {
    agent any
    

    stages {

        stage('Build'){
            steps {
                echo "Running build..."
            }
        }
       
        stage('Test'){
            steps {
                echo "Running tests..."
            }
        }
       
        stage('Deploy'){
            steps {
		    snDevOpsChange()
                echo "Running deploy to PROD"
            }
        }
       
	}
 
 }
