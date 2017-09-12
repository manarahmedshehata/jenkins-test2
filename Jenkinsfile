pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
               currentBuild
                sh 'echo "$currentBuild.currentResult"';
                
            }
        }
        
    }
}
