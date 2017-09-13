pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh'env'
                sh'cat dep.yaml'
                sh'cat dep.yaml | sed -i s/EXTERNAL_IP/1.2.3.4/ dep.yaml | cat dep.yaml' 
                 
                sh'cat dep.yaml'
                
            }
        }
        
    }
}
