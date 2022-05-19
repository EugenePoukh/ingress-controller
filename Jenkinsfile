node {
    
    stage('Deploy') {
        echo "Deploy To K8S Cluster Stage"
        sh "/usr/local/bin/kubectl apply -f dev-deployment.yaml -n develop --context gke_protean-sphinx-344415_us-central1-c_practice"
    }
}
