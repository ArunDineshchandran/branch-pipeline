pipeline {
    agent any

    stages {
        stage('Test') {
            steps {
                echo 'Running tests...'
               
            }
        }

        stage('Build') {
            steps {
                echo 'Building the project...'
                
            }
        }
	    stage('Deploy') {
            steps {
                echo 'Deploy the project...'
                
            }
        }
	    
	post {

	sucess{
	echo "Build sucess"
	}
	
	failure{
        echo "Build fail"
        }

	}
    }
}

