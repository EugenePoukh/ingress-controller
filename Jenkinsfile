pipeline {
    agent any

    stages {
        stage('Deployment') {
            steps {
              # echo "Deploy deployment"
              # sh "export KUBECONFIG='/root/.kube/config'"
	      # sh "/usr/local/bin/kubectl apply -f dev-deployment.yaml -n develop"
                sh ""/usr/local/bin/kubectl get pods -A"
               }
        }
             

    }
}

