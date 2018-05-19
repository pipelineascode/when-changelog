pipeline {
    agent any
	
    stages {
        stage('Example') {
		
			when{
				changeRequest()
			}
		
            steps {                
                echo 'Hello World chaning request'
            }
        }
    }
}
