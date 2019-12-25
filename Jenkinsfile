pipeline {
    agent any
	
    stages {
        stage('Build') {
		
			when{
				tag "4.0"
			}
		
            steps {                
                echo 'Hello World building tag'
            }
        }
    }
}
