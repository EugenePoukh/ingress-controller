node {
    
    stage('Deploy') {
        echo "Deploy To K8S Cluster Stage"
        sh "/usr/local/bin/kubectl apply -f dev-deployment.yaml -n develop --token ya29.a0ARrdaM-6cx-4wpfereOzV_W6Q98C0tNIvbEvhRzlUMUz3gaSGRhJR4U9WNn7FjnbsRx6wrpW2ediyAWp0egtpESGDD3_EaJjMyR4sSdm1N8br7hITEoTYdbOQTSX-o2xe2YBXB8w15kpBSs76twFUme5_BtVrCMqF18FZ0E --server https://35.193.71.151"
    }
}
