pipeline {
    agent any
	
    stages {
        stage('Build') {
            steps {

                // Run Maven on a Unix agent.
                bat "mvn clean package"
            }

        }
    }
}