node {
    
    stage('Deploy') {
        echo "Deploy To K8S Cluster Stage"
        sh "/usr/local/bin/kubectl apply -f dev-deployment.yaml --context practice-n develop"
    }
}
