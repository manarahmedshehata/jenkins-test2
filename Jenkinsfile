pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                env
                sh 'echo "$currentBuild.currentResult"';
                
            }
        }
        
    }
}
