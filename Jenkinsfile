pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh'env'
                sh'sed -i s/EXTERNAL_IP/$HOSTNAME/ dep.yaml' 
                sh'cat dep.yaml'
                //sh 'params'
                
            }
        }
        
    }
    
}
