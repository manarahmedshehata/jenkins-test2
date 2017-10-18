pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh'env'
                
                sh'export x=123'
                sh'env'
                sh'sed -i s/EXTERNAL_IP/test22/ dep.yaml' 
                sh'cat dep.yaml'
                //sh 'params'
                
            }
        }
        
    }
    
}
