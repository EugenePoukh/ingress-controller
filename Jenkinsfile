node {
    
    stage('Deploy') {
        echo "Deploy To K8S Cluster Stage"
        sh "export KUBECONFIG='/root/.kube/config'"
	sh "/usr/local/bin/kubectl apply -f dev-deployment.yaml -n develop --token eyJhbGciOiJSUzI1NiIsImtpZCI6IlhaN2F3aHdDM3lQczJZd0JlQ0gtSlB4SEtKSW1EWU83TTVGZmxNRmZOMkkifQ.eyJpc3MiOiJrdWJlcm5ldGVzL3NlcnZpY2VhY2NvdW50Iiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9uYW1lc3BhY2UiOiJkZXZlbG9wIiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9zZWNyZXQubmFtZSI6ImplbmtpbnMtdG9rZW4tNXZ2OTYiLCJrdWJlcm5ldGVzLmlvL3NlcnZpY2VhY2NvdW50L3NlcnZpY2UtYWNjb3VudC5uYW1lIjoiamVua2lucyIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VydmljZS1hY2NvdW50LnVpZCI6IjIzMDU3NTliLWFhNzUtNGNkYy1iZDVkLTcwMDhjNzNiNzBkMiIsInN1YiI6InN5c3RlbTpzZXJ2aWNlYWNjb3VudDpkZXZlbG9wOmplbmtpbnMifQ.HbljwHJtEIVvzdZ7e-fX9MtSodbqTXV5lh_IQbgQHesx2CytG1v6jOu82a8ZK-dDDmtGEYuO5PD2LrfMdSwdUQSPOwCravfmTJMoSk4rXJCIU0jVlfz_lY6PVf1NENC2DI64vgfMZ_2AUhy43I81ZtkTNlOoXZSxtGnwlVJlgQ09stuzdmVlhMRpGEZczBDJcpqCsFw-4khPNmEJEARFcgj6GMW_sM0rtWvaOqz952Sy8qRJIksUJmC80F-HqJqp0GNpp5uWHdtvdfQmCzkUMIRqvi_q4T_7QO4ATjb6r7GRM0JqY0iRJ8xu8gYhp8eIRf4hAb8SI_i0a-eAI57q2Q --server https://35.193.71.151"
    }
}
