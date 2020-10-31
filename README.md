## Cloud Architecture and Deployment

During the configuration of a cloud Network from my cyberclass the files in this repository was used.

Using the azure portal for this configuration and deployment, a resource group was first created that contained all that the other resources that were created later on used.
Next was to create the Virtual network which enabled the Virtual machines we created afterwards communicate securely with each other. Before creating the virtual machines, I created a Network security group which was added to my resource group. The network security group is important because that's were the inbound and outbaound rules are set to secure the network.
I created 4 VMs, the first was the "Jumpbox" which ran the Docker containers while the other 3 VMs were Web-VMs running vulnerable DVWA containers.
#Note: All resources were created and deployed in the same availability region.


##ELK (Elasticsearch, Logstash, and Kibana) Server

