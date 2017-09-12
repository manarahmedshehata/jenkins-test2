pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh'env'
                sh'currentBuild'
                sh 'echo "$currentBuild.currentResult"';
                
            }
        }
        
    }
}
