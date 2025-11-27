pipeline {
    // --- THIS IS THE REQUIRED FIX ---
    agent any 

    stages {
        stage('build') {
            steps {
                // This assumes 'node' command is available on the agent selected by 'agent any'
                sh 'node --version' 
            }
        }
    }
}