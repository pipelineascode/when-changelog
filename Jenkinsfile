pipeline {
    agent any
	
    stages {
        stage('Example') {
		
			when{
				changeRequest title:"when-pr"
			}
		
            steps {                
                echo 'Hello World changing request'
            }
        }
    }
}
