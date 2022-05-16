pipeline {
    agent any

    stages {
        stage('Deployment') {
            steps {
               echo "Deploy deployment"
	       sh "/usr/local/bin/kubectl apply -f dev-deployment.yaml -n develop"
               }
        }
        stage('Service') {
            steps {
               echo "Deploy service"
               sh "/usr/local/bin/kubectl apply -f dev-service.yaml -n develop"
               }
        }
        stage('Ingress') {
            steps {
               echo "Deploy ingress rules"
               sh "/usr/local/bin/kubectl apply -f dev-ingress.yaml -n develop"
               }
        }

    }
}

