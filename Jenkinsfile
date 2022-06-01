pipeline {
    agent any
    environment {
    KUBECONFIG = '/root/.kube/config'
    }
    stages {
        stage('Deployment') {
            steps {
               echo "Deploy deployment"
	       sh "/usr/local/bin/kubectl apply -f /root/YAML/dev -n develop"
               }
        }
        }

    }


