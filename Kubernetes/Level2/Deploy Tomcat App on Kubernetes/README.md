Create a namespace named tomcat-namespace-datacenter.

Create a deployment for tomcat app which should be named as tomcat-deployment-datacenter under the same namespace you created. Replica count should be 1, the container should be named as tomcat-container-datacenter, its image should be gcr.io/kodekloud/centos-ssh-enabled:tomcat and its container port should be 8080.

Create a service for tomcat app which should be named as tomcat-service-datacenter under the same namespace you created. Service type should be NodePort and nodePort should be 32227.
