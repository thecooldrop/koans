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
3. Rewrite recipes in Quarkus
4. Rewrite recipes in Spring Boot
5. In Recipes app in Spring Boot implement registration of users in database (once relational, once dynamodb)
6. In Recipes app in Quarkus implement registration of users in database (once relational, once dynamodb)
7. In serverless version of the application implement the registration of new users
8. Implement user registration for recipes app via Cognito:
   1. in Quarkus
   2. in Spring boot
   3. in Serverless application
9. Implement user authorization for self-managed user registration in recipes app:
   1. in Quarkus
   2. in Spring Boot
10. Implement user authorization for cognito managed users in recipes app:
11. in Quarkus
12. in Spring Boot
13. Serverless
