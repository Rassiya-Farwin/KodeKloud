1. Click Jenkins > Manage Jenkins > Manage Plugins and click Available tab. Search for Pipeline Git, SSH Pipeline & SSH Build Agents  plugin and click Download now and install after restart

2. install java on storage server
<img width="1024" height="484" alt="image" src="https://github.com/user-attachments/assets/51284519-3003-49b5-9e70-83f1792ac1e1" />

3. Add credentials to jenkins


Manage Jenkins > Credentials > System > Global credentials (unrestricted)

<img width="1065" height="843" alt="image" src="https://github.com/user-attachments/assets/502b4b60-8e7a-426d-ba73-4e88e52922fe" />


4. Configure the Slave Node (Storage Server)
need to create a new permanent slave node in Jenkins to represent the Storage Server.

Manage Jenkins > Nodes > New node

<img width="1196" height="447" alt="image" src="https://github.com/user-attachments/assets/373bc926-ccc2-48dc-9d2e-550fb04b3701" />


<img width="1805" height="950" alt="image" src="https://github.com/user-attachments/assets/61eeb1ba-12bb-4bf6-9b48-a1fe6b95e517" />


Setup Credentials for GIT user sarah
<img width="972" height="823" alt="image" src="https://github.com/user-attachments/assets/f07b553a-ac54-45a1-b613-d80b76777d86" />
