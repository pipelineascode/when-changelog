pipeline {
    agent any
	
    stages {
        stage('Example') {
		
			when{
				changeRequest title:"when-pr123"
			}
		
            steps {                
                echo 'Hello World changing request'
            }
        }
    }
}
