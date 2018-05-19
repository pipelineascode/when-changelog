pipeline {
    agent any
	
    stages {
        stage('Example') {
		
			when{
				changeset glob: "*.js"
			}
		
            steps {                
                echo 'Hello World JS'
            }
        }
    }
}
