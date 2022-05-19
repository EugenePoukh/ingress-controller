node {
    
    stage('Deploy') {
        echo "Deploy To K8S Cluster Stage"
        sh "/usr/local/bin/kubectl apply -f dev-deployment.yaml -n develop --token ya29.a0ARrdaM88ocacM2yq50aT_cQ81GvmAbAmMUUTkMUSWA4Hx7dCE3TLRl7kaBWPD922ucceJRDds8a2V3EVOcpLNFhozCAR9uL4LLggWCNojoqjhPBgy3HEpx1Fr7ifkkLYIKVD5RG8tlQsrYbN02tvKoCueiJZzusR0UNG35o --server apiserver.35.193.71.151"
    }
}
