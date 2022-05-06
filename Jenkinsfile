pipeline {
    agent any

    stages {
        stage('Deployment') {
            steps {
               echo "Deploy deployment"
	       sh "kubectl apply -f dev-deployment.yaml -n develop"
               }
        }
        stage('Service') {
            steps {
               echo "Deploy service"
               sh "kubectl apply -f dev-service.yaml -n develop"
               }
        }
        stage('Ingress') {
            steps {
               echo "Deploy ingress rules"
               sh "kubectl apply -f dev-ingress.yaml -n develop"
               }
        }

    }
}

