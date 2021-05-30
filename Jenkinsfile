pipeline {
    
    agent { label "slave" }

    stages {
              
        stage('Deploy to k8s cluster') {
            steps {
            sh 'kubectl apply -f app-deploy.yml'
            }
        }

        stage('Display pods') {
            steps {
            sh 'kubectl get pods '
            }
        }
     
      
        
    }
}
