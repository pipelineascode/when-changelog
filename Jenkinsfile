pipeline {
    agent any
	
    stages {
        stage('Example') {
		
			when{
				changeset "*.js"
			}
		
            steps {                
                echo 'Hello World JS'
            }
        }
    }
}
