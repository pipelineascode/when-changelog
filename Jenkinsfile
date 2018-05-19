pipeline {
    agent any
	
    stages {
        stage('Example') {
		
			when{
				//buildingTag()
				tag "7.0"
			}
		
            steps {                
                echo 'Hello World building tag'
            }
        }
    }
}
