pipeline {
    agent any
    stages {
        stage('Build Master') {
            when {
                branch 'master'
            }
            steps {
                echo 'Building'
            }
        }
        stage('Build Dev') {
            when {
                branch 'dev'
            }
            steps {
                echo 'Building'
            }
        }
    }
}