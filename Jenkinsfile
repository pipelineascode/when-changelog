pipeline {
    agent any
	
    stages {
        stage('Example') {
		
			when{
				buildingTag()
			}
		
            steps {                
                echo 'Hello World building tag'
            }
        }
    }
}
