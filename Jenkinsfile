pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh'env'
                sh'cat dep.yaml'
                sh'cat dep.yaml | sed s/\$EXTERNAL_IP/hiiiiiiiiiii/'
                
                sh'cat dep.yaml'
                
            }
        }
        
    }
}
