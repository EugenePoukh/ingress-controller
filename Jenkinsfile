pipeline {
    agent any

    stages {
        stage('Deployment') {
            steps {
               echo "Deploy deployment"
	       kubectl apply -f dev-deployment.yaml -n develop
               }
        }
        stage('Service') {
            steps {
               echo "Deploy service"
               kubectl apply -f dev-service.yaml -n develop
               }
        }
        stage('Ingress') {
            steps {
               echo "Deploy ingress rules"
               kubectl apply -f dev-ingress.yaml -n develop
               }
        }

    }
}

