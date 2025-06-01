# redis-cluster
**Deploy Redis Cluster on Kubernetes**

*The project architecture will be as follows:*


![redis-cluster](https://github.com/user-attachments/assets/9f860d74-a379-454f-b99a-630756e142af)


*Intalling:*
helm install redis-cluster redis-cluster-12.0.2.tgz -f values.yaml -n [Your Namespace]
