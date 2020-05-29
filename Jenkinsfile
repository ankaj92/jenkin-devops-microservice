pipeline {
	agent any
		stages {
			stage('build'){
				steps {
					echo "Build"
				}		
			}
			stage('Test') {
				steps {
					echo "Testing"
				}	
			}
			stage('Integration') {
				steps {
					echo "Integration Testing"
				}	
		}
	}	
}

post {
	always {
		echo 'i ran yey!'
	}
	success {
		echo 'i\'m successfull yey'
		}
	failure {
		echo 'i\'m failed'
	}
}
