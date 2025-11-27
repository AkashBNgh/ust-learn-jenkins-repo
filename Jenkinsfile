pipeline {
    agent any 

    // The triggers block belongs here, at the top level of the pipeline
    triggers {
        // This schedules the build for roughly 4:00 AM, Monday through Friday
        cron('* * * * *')
    }

    stages {
        stage('Build') {
            steps {
                // using 'bat' is correct for Windows; use 'sh' for Linux
                bat 'node --version' 
            }
        }
    }
}