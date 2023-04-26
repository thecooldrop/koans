# Koans

1. Deploy logging solution to local Kubernetes cluster
   1. Deploy FluentBit to local Kubernetes cluster
   2. Deploy OpenSearch to local Kubernetes cluster
   3. Deploy OpenSearch Dashboard to local Kubernetes cluster
   4. Configure Fluentbit to collect logs from all cluster nodes ( simulate multiple nodes )
   5. Configure FluentBit to forward logs to Opensearch
   6. Deploy multiple pods to cluster and ensure that we can see in opensearch where the logs are coming from
   7. Deploy FluentD as intermediary
   8. Configure Fluentbit to forward logs to FluentD, which forwards them to Opensearch
2. Use Argo Workflows to compile Java application
