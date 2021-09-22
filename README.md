# wordpress_deployed_Kubernetes_Multinode_Cluster

### 🔅 Provision the entire infrastructure VPC, Subnets and Launched ec2-instances on AWS Cloud using Terraform for master node and slave nodes
### 🔅 Created seperate ansible roles that will configure master node and slave node of the kubernetes
### 🔅 Launch a wordpress and mysql database connected to it in the respective slaves
### 🔅 Expose the wordpress pod and client able hit the wordpress ip with its respective port


# Key features of the K8s Multinode Cluster

#### Entire configuration done with end to end automation 
#### Provision the Infrastructure and sameway destroy the infrastructure within seconds done with the help of Instrastructure as code tool Terraform 
### Used Dynamic inventory to fetch the details of the aws instances
### Configure the Kubernetes Multi node Cluster in the aws cloud using the Configuration management tool Ansible
