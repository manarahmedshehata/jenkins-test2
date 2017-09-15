pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh'env'
                /*
                sh'cat dep.yaml'
                sh'sed -i s/EXTERNAL_IP/test22/ dep.yaml' 
                 
                sh'cat dep.yaml'*/
                //sh 'params'
                
            }
        }
        
    }
     post {
        success {    // notify users when the Pipeline fails
            mail(to: 'manarahmedshehata@gmail.com', subject: "Failed Pipeline", body: "Something is wrong.")
        }
    }
}
