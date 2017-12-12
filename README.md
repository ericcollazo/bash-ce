# powershell-ce
Bash script using **docker-machine** to create a **Docker CE** swarm cluster with **UCP** on **DigitalOcean** VM's.
1. Add a text file named **variables.txt** to the root folder.
2. In the text file, add your DigitalOcean API key as listed below:

   `<API-KEY>`

3. Using **Bash**, execute the following command in the root folder containing the script:

   `./create-docker-cluster.ps1`
   
4. To execute commands within a cluster node:

   `docker-machine ssh <NODE NAME>`
   
5. To take down the cluster:

   `./remover-docker-cluster.ps1`
