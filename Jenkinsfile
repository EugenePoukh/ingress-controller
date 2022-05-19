node {
  stage('Apply Kubernetes files') {
    steps  {
      sh 'kubectl apply -f dev-deployment.yaml -n develop'
    }
  }
}

