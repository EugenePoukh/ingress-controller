pipeline {
agent any
stages {
    stage('Build1'){
        steps{
            script{
                sh 'export KUBECONFIG='/root/.kube/config''
		sh 'whoami'
		sh '/usr/local/bin/kubectl apply -f dev-deployment.yaml -n develop'
            }
        }
    }
}
}
