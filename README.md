# quarkus-kubernetes-management-metrics-reproducer

Reproduction steps:
1. Run `mvn clean package`
2. Open `target/kubernetes/kubernetes.yml`
3. Notice that the prometheus label refer to the incorrect port 
