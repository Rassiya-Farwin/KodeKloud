Create a namespace named as httpd-namespace-xfusion.

Create a deployment named as httpd-deployment-xfusion under newly created namespace. For the deployment use httpd image with latest tag only and remember to mention the tag i.e httpd:latest, and make sure replica counts are 2.

Create a service named as httpd-service-xfusion under same namespace to expose the deployment, nodePort should be 30004.
