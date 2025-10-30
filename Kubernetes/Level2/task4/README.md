Create a namespace datacenter. Create a deployment called httpd-deploy under this new namespace, It should have one container called httpd, use httpd:2.4.27 image and 2 replicas. The deployment should use RollingUpdate strategy with maxSurge=1, and maxUnavailable=2. Also create a NodePort type service named httpd-service and expose the deployment on nodePort: 30008.


Now upgrade the deployment to version httpd:2.4.43 using a rolling update.


Finally, once all pods are updated undo the recent update and roll back to the previous/original version.
<img width="980" height="321" alt="image" src="https://github.com/user-attachments/assets/b2ad9e6f-411e-4bef-b7c8-331a252bbde5" />
