pipeline {
    agent any
    environment {
    KUBECONFIG = '/root/.kube/config'
    }
    stages {
        stage('Deployment') {
            steps {
               echo "Deploy deployment"
	       sh "/usr/local/bin/kubectl apply -f /root/YAML/dev-deployment.yaml -n develop"
               }
        }
        stage('Service') {
            steps {
               echo "Deploy service"
               sh "/usr/local/bin/kubectl apply -f /root/YAML/dev-service.yaml -n develop"
               }
        }
        stage('Ingress') {
            steps {
               echo "Deploy ingress rules"
               sh "/usr/local/bin/kubectl apply -f /root/YAML/dev-ingress.yaml -n develop"
               }
        }

    }
}

