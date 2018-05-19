pipeline {
    agent any
	
    stages {
        stage('Example') {
		
			when{
				changelog 'DEPENDENCY'
			}
		
            steps {                
                echo 'Hello World 1'
            }
        }
    }
}
