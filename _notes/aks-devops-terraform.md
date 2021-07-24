=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
# Azure AKS Kubernetes - Masterclass | Azure DevOps, Terraform

https://www.udemy.com/course/azure-kubernetes-service-with-azure-devops-and-terraform/learn/lecture/23628290#overview

This class covers both manually creating AKS cluster and all that it requires, as well as how to script the provisioning in Terraform

*** how to use repo ***
FORK the class code repo in Github, do not CLONE it to local ... that way I have my own version in a code repo that I can both make my changes AND refresh from original

README.me file in each section has the text of the sample code to copy/paste

cd /Users/kthomson/Repos/StackSimplify/Masterclass
git clone git@github.com:Biker93/azure-aks-kubernetes-masterclass.git
git clone git@github.com:Biker93/azure-devops-github-acr-aks-app1.git
git clone git@github.com:Biker93/azure-devops-aks-kubernetes-terraform-pipeline.git
git clone git@github.com:Biker93/docker-fundamentals.git

ls -la
drwxr-xr-x  34 kthomson  staff  1088 Jul 17 16:14 azure-aks-kubernetes-masterclass
drwxr-xr-x   8 kthomson  staff   256 Jul 22 00:38 azure-devops-aks-kubernetes-terraform-pipeline
drwxr-xr-x  12 kthomson  staff   384 Jul 22 00:36 azure-devops-github-acr-aks-app1
drwxr-xr-x  11 kthomson  staff   352 Jul 22 00:39 docker-fundamentals


## Course Overview

Welcome to this Amazing course on Azure AKS Kubernetes - Masterclass | Azure DevOps, Terraform.
Below is the list of modules covered in this course.

## Course Sections
1. Introduction
2. Create Azure AKS Cluster using Azure Portal
3. Docker Fundamentals
4. Imperative Method: Kubernetes Fundamentals using kubectl
5. Declarative Method: Kubernetes Fundamentals using YAML
6. Azure Disks for AKS Storage
   Custom Storage Class, PVC, and PV
   AKS default Storage class, PVC and PV
   User Management Web Application Deployment with MySQL as storage using Storage Class, PVC, and PV
7. Azure MySQL for AKS Storage
8. Kubernetes Secrets
9. Azure Files for AKS Storage
10. Ingress Basics
11. Ingress Context path based Routing
12. Azure DNS Zones - Delegate domain from AWS to Azure
13. Ingress and External DNS with Azure DNS Zones
14. Ingress Domain Name based Routing with External DNS
15. Ingress SSL with LetsEncrypt
16. Kubernetes Requests & Limits
17. Kubernetes Namespaces
    Kubernetes Namespaces - Imperative
    Kubernetes Namespaces - Limit Range
    Kubernetes Namespaces - Resource Quota
18. Azure Virtual Nodes for AKS
    Azure Virtual Nodes Basics
    Azure AKS Virtual Nodes Mixed Mode Deployments
19. Azure Container Registry for AKS
    Integrate Azure Container Registry ACR with AKS
    Azure AKS Pull Docker Images from ACR using Service Principal
    Pull Docker Images from ACR using Service Principal and Run on Azure Virtual Nodes
    Azure DevOps with AKS Cluster
20. Azure DevOps - Build and Push Docker Image to Azure Container Registry
21. Azure DevOps - Build, Push to ACR and Deploy to AKS
22. Azure DevOps - Create Starter Pipeline
23. Azure DevOps - Release Pipelines
24. Azure AKS - Enable HTTP Application Routing AddOn
    Azure AKS Authentication with Azure AD and Kubernetes RBAC
25. Azure AKS Cluster Access with Multiple Clusters
26. Azure AD Integration with Azure AKS for Authentication
27. Kubernetes RBAC Role & Role Binding with Azure AD on AKS
28. Kubernetes RBAC Cluster Role & Role Binding with AD on AKS
29. Azure AKS Cluster Autoscaling
30. Azure AKS - Horizontal Pod Autoscaler HPA
31. Azure AKS Production Grade Cluster Design using AZ AKS CLI
    Create Azure AKS Cluster using AZ AKS CLI
    Create Azure AKS Linux, Windows, and Virtual Node Pools
    Deploy Apps to Azure AKS Linux, Windows, and Virtual Node Pools

32. Provision Azure AKS Clusters using Terraform
    Terraform Command Basics
    Terraform Language Basics
    Provision AKS Cluster using Terraform
    Create AKS Cluster Linux and Windows Node Pools
    Create an Azure AKS Cluster using Custom Virtual Network

33. Provision Azure AKS using Terraform & Azure DevOps


## Azure Services Covered
Azure Kubernetes Service
Azure Disks
Azure Files
Azure MySQL Database
Azure Storage Accounts
Azure Cloud Shell
Azure Load Balancer
Azure DNS Zones
Azure Container Registries ACR
Azure Container Registries ACR with Azure Service Principal
Azure DevOps - Build Pipelines with ACR & Github Repositories
Azure DevOps - Release Pipelines with AKS
Azure Public IP Address
Azure Standard Load Balancer
Azure Virtual Networks
Azure Active Directory
Azure Container Instances - Virtual Nodes
Azure AKS Windows and Linux User NodePools
Azure Managed Service Identity - MSI
Azure Virtual Machine Scale Sets
Azure Log Analytics Workspaces for Azure Monitor


## Kubernetes Concepts Covered
Kubernetes Architecture
Pods
ReplicaSets
Deployments
Services - Load Balancer Service
Services - Cluster IP Service
Services - External Name Service
Services - Ingress Service
Services - Ingress SSL & SSL Redirect
Services - Ingress & External DNS
Services - Domain Name based Routing
Imperative - with kubectl
Declarative - Declarative with YAML
Secrets
Init Containers
Requests & Limits
Namespaces - Imperative
Namespaces - Limit Range
Namespaces - Resource Quota
Storage Classes
Persistent Volumes
Persistent Volume Claims
Services - Load Balancers
Annotations
HPA - Horizontal Pod Autoscaler
CA - Cluster Autoscaler
Config Maps
RBAC - Role & Role Bindings
RBAC - Cluster Role & Cluster Role Bindings
Virtual Kubelet
Secrets - Image Pull Secrets


## Each of my courses come with
Amazing Hands-on Step By Step Learning Experiences
Real Implementation Experience
Friendly Support in the Q&A section
30 Day "No Questions Asked" Money Back Guarantee!

## What you’ll learn
You will learn to build Azure AKS Production grade clusters using Azure AKS CLI
You will learn terraform from basics and create terraform manifests for provisioning Azure AKS Production grade clusters
You will learn to provision Azure AKS Clusters using Terraform and Azure DevOps.
You will learn 30+ kubernetes concepts and use 21 Azure Services in combination with Azure AKS
You will implement DevOps concepts with Azure DevOps Continuous Integration Pipelines and Continuous Deliver Pipelines also called Release Pipelines
You will write Azure DevOps CI Pipelines from scratch using Starter Pipelines
You will write kubernetes manifests with confidence after going through live template writing sections
You will learn Kubernetes Fundamentals in both imperative and declarative approaches
You will learn writing & deploying k8s manifests for storage concepts like storage class, persistent volume claim pvc, mysql
You will learn to switch from native Azure Disks to Azure MySQL Database using k8s external name service
You will learn writing and deploying load balancer k8s manifests for Azure Standard Load Balancer
You will learn writing ingress k8s manifests by enabling features like context path based routing, domain name based routing, SSL with LetsEncrypt and External DNS.
You will learn writing k8s manifests for Azure Virtual Nodes (serverless) and do mixed mode workload deployments in both Azure Linux NodePools and Virtual Nodes.
You will learn using ACR - Azure Container Registry in combination with AKS in 3 ways (ACR Attach, using Service Principal, on Virtual Nodes)
You will learn to enable Autoscaling features like HPA & Cluster Autoscaler
You will learn Docker fundamentals by implementing usecases like download image from Docker Hub and run on local desktop and build an image locally, test and push to Docker Hub.
You will master many kubectl commands over the process
You will learn to integrate Azure AKS with Azure Active Directory for AKS Admins to be created managed in Azure Active Directory
You will learn Kubernetes RBAC concepts like role, role-binding, cluster role, cluster role binding in combination with Azure AD for Azure AKS granular level access control
Are there any course requirements or prerequisites?
You must have an Azure Cloud account to follow with me for hands-on activities.
You dont need to have any basic Docker or kubernetes knowledge to start this course.
Who this course is for:
Azure Architects or Sysadmins or Developers who are planning to master Azure Kubernetes Service (AKS) for running applications on Kubernetes
Any beginner who is interested in learning kubernetes on cloud using Azure AKS.
Any beginner who is interested in learning Azure DevOps, Terraform to provision Azure Kubernetes Clusters
Instructor
User photo
Kalyan Reddy Daida | DevOps & SRE Architect on AWS, Azure & Google Cloud Platforms
Best Selling Instructor, Docker, Kubernetes, Terraform, SRE

## About Me
I'm Kalyan Reddy Daida, an Architect with 15 Years of experience in designing complex Infrastructure solutions, Java programming and design with major payroll clients across the world.
I have special interests in cloud technologies and cloud-native solutions like Kubernetes and Istio. I am passionate about learning new technology and teaching.
I have extensive experience in architecting, designing and implementing solutions on AWS.

## About Stack Simplify
At Stack Simplify we focus on implementing real world scenarios in our courses.
Each of our courses focuses on providing hands-on experience to students in learning new technology in a step-by-step and interesting manner.



=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
# Section 0: Introduction
7/15/21

REPO: 00-Pre-requisites


=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
# 3 Github repo links

Azure AKS Kubernetes - Masterclass | Azure DevOps, Terraform: https://github.com/stacksimplify/azure-aks-kubernetes-masterclass

Azure DevOps for Kubernetes Workloads running on Azure AKS Cluster: https://github.com/stacksimplify/azure-devops-github-acr-aks-app1

Provision Azure AKS Cluster using Terraform and Azure DevOps: https://github.com/stacksimplify/azure-devops-aks-kubernetes-terraform-pipeline

Docker Fundamentals: https://github.com/stacksimplify/docker-fundamentals

Presentation with 250 Slides outlining the various architectures and designs we are going to do in this course: https://github.com/stacksimplify/azure-aks-kubernetes-masterclass/tree/master/ppt-presentation

Important Note: Please go to these repositories and FORK these repositories and make use of them during the course.

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
# Section 1: Create Azure AKS Cluster
7/21/21
REPO: 01-Create-AKS-Cluster

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
# 5 create AKS CLuster using portal

need DS2_v2 to get enhanced networking ... and that is required for other components, like MySQL

each node: 2 vCPU 7GB RAM 14GB Storage, $0.146/hr  $3.50/day  $106/mo
https://azure.microsoft.com/en-us/pricing/calculator/?service=kubernetes-service

## Why Managed Identity when creating Cluster?
https://docs.microsoft.com/en-us/azure/aks/use-managed-identity

https://bridgecrew.io/thank-you-webinar/?210616&submissionGuid=3ffe6ad1-9de0-476c-827a-daac3d9870f7


=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
# 6 Cloud Shell

this needs a storage account, but it doesn't see my Enterprise subscription, only AIT Hosting and MSDN .... 

problem was the browser was not looged into the MSDN kthomson@air.org / Default Directory account  thru LinkedIn

az aks get-credentials --resource-group aks-rg1 --name aksdemo1
Merged "aksdemo1" as current context in /home/kip/.kube/config
kip@Azure:~$



=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
# Base image rebuild Best Practices

https://docs.microsoft.com/en-us/azure/aks/operator-best-practices-container-image-management#automatically-build-new-images-on-base-image-update

https://docs.microsoft.com/en-us/azure/container-registry/container-registry-tutorial-base-image-update

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#






=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
# Section 32: Provision AKS Cluster with Terraform
7/15/21: worked on this section first, to learn Terraform quickly

REPO: 24-04-Create-AKS-NodePools-using-Terraform

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
# 170 Terraform Basics

blah blah blah about reason to use Terraform and Terraform Cloud

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
# 171 Install pre-req
already done from Terraform class

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
# 172 Providers and Init
already done from Terraform class

cloud providers
local utility providers ... e.g "random" number/name generator

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
# 173 Plan, Validate, Apply
already done from Terraform class

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
# 180 Create Setting block

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
# 185 Migrate storage from Local to Azure Storage account

Use portal to create Stroage Account (and RG for Storage Account)

*** Must use the same subscription as the other resources, otherwise "terraform init" will fail

Deployment name:terraformstorageaksclass_1626611270282
Subscription:Visual Studio Enterprise   cf71d4cd-095a-47ec-bca0-060c571abedf
Resource group:terraform-storage-rg
Start time:7/18/2021, 8:27:51 AM
Correlation ID:059892b7-9612-4b2d-a648-ac9eaff14d26

now create a container in that account for terraform state file: tfstatefiles

and finally, go into that container upload the cuurent terraform.tfstatefile


n.b. I initially created the rg, storage account and container in the MSDN subscription.
when terraform init failed, I moved it to Enterprise ...
but the original RG is still there, just empty



=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
# 186 Provision AKS Cluster using Terraform

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
# 187 Create SSH keys

# Create Folder
mkdir $HOME/.ssh/aks-prod-sshkeys-terraform

# Create SSH Key
ssh-keygen \
    -m PEM \
    -t rsa \
    -b 4096 \
    -C "azureuser@myserver" \
    -f ~/.ssh/aks-prod-sshkeys-terraform/aksprodsshkey \
    -N mypassphrase

# List Files
ls -lrt $HOME/.ssh/aks-prod-sshkeys-terraform
`

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
# 188 Create LOg Analytics WOrkspaec, AD Group, ...

az aks get-versions --location eastus -o table
KubernetesVersion    Upgrades
-------------------  ------------------------
1.21.1(preview)      None available
1.20.7               1.21.1(preview)
1.20.5               1.20.7, 1.21.1(preview)
1.19.11              1.20.5, 1.20.7
1.19.9               1.19.11, 1.20.5, 1.20.7
1.18.19              1.19.9, 1.19.11
1.18.17              1.18.19, 1.19.9, 1.19.11


https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/kubernetes_cluster
All arguments including the client secret will be stored in the raw state as plain-text. Read more about sensitive data in state.

🥃 terraform-manifests-aks (master) 💍 terraform apply v1plan.out
azurerm_kubernetes_cluster.aks_cluster: Creating...
azurerm_kubernetes_cluster.aks_cluster: Still creating... [10s elapsed]
...
azurerm_kubernetes_cluster.aks_cluster: Still creating... [3m30s elapsed]
azurerm_kubernetes_cluster.aks_cluster: Creation complete after 3m38s [id=/subscriptions/cf71d4cd-095a-47ec-bca0-060c571abedf/resourcegroups/terraform-aks-dev/providers/Microsoft.ContainerService/managedClusters/terraform-aks-dev-cluster]

Apply complete! Resources: 1 added, 0 changed, 0 destroyed.

Outputs:

aks_cluster_id = "/subscriptions/cf71d4cd-095a-47ec-bca0-060c571abedf/resourcegroups/terraform-aks-dev/providers/Microsoft.ContainerService/managedClusters/terraform-aks-dev-cluster"
aks_cluster_kubernetes_version = "1.20.7"
aks_cluster_name = "terraform-aks-dev-cluster"
azure_ad_group_id = "cae02bbc-ffa3-4efd-af9b-527c40d5a1b7"
azure_ad_group_objectid = "cae02bbc-ffa3-4efd-af9b-527c40d5a1b7"
latest_version = "1.20.7"
location = "eastus"
resource_group_id = "/subscriptions/cf71d4cd-095a-47ec-bca0-060c571abedf/resourceGroups/terraform-aks-dev"
resource_group_name = "terraform-aks-dev"
versions = tolist([
  "1.18.17",
  "1.18.19",
  "1.19.9",
  "1.19.11",
  "1.20.5",
  "1.20.7",
])


=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
# 189-193 AKS Cluster

ADMIN
az aks get-credentials --resource-group terraform-aks-dev --name terraform-aks-dev-cluster --admin
.kube/config has:
- name: clusterAdmin_terraform-aks-dev_terraform-aks-dev-cluster


# Get Full Cluster Information
az aks show --resource-group terraform-aks-dev --name terraform-aks-dev-cluster
az aks show --resource-group terraform-aks-dev --name terraform-aks-dev-cluster -o table

# Get AKS Cluster Information using kubectl
kubectl cluster-info

# List Kubernetes Nodes
kubectl get nodes

kubectl get all --all-namespaces

USER
az aks get-credentials --resource-group terraform-aks-dev --name terraform-aks-dev-cluster --overwrite-existing
.kube/config has:
- name: clusterUser_terraform-aks-dev_terraform-aks-dev-cluster

go to Portal/active directory/Groups/
open the (trraform created) terraform-aks-dev2-cluster-administrators
click on "Members" and add the user (create at the very beginning in AD)
taksadmin1   taksadmin1@kthomsonair.onmicrosoft.com

Firefox is my pcrp_kthomson account
  terminal can d.host test/prod

Safari window 1 is my kthomson account/token
Kip Thomson  kthomson_air.org#EXT#@kthomsonair.onmicrosoft.com  kthomsonair.onmicrosoft.com
https://portal.azure.com/#home
  access to everything
https://myaccount.microsoft.com/?ref=MeControl   (click on user icon upper right)
  access to Azure account ... everything

Safari window 2 is taksadmin1  account/token
taksadmin1   taksadmin1@kthomsonair.onmicrosoft.com
https://myaccount.microsoft.com
  account is JUST for authentication to AKS services
https://portal.azure.com/#blade/HubsExtension/BrowseAll
  acct has no Azure permissions, no access to the subscription, so can't access anything
  left top hamburger at best goes to Dashboard ... but it is empty

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
# 194 Nodepools

StackSimplify/Masterclass/azure-aks-kubernetes-masterclass/24-Azure-AKS-Terraform/24-04-Create-AKS-NodePools-using-Terraform

azurerm_kubernetes_cluster_node_pool.linux101: Creating...
azurerm_kubernetes_cluster_node_pool.win101: Creating...
...
azurerm_kubernetes_cluster_node_pool.linux101: Creation complete after 2m36s [id=/subscriptions/cf71d4cd-095a-47ec-bca0-060c571abedf/resourcegroups/terraform-aks-dev/providers/Microsoft.ContainerService/managedClusters/terraform-aks-dev-cluster/agentPools/linux101]
azurerm_kubernetes_cluster_node_pool.win101: Still creating... [2m40s elapsed]
...
azurerm_kubernetes_cluster_node_pool.win101: Creation complete after 5m37s [id=/subscriptions/cf71d4cd-095a-47ec-bca0-060c571abedf/resourcegroups/terraform-aks-dev/providers/Microsoft.ContainerService/managedClusters/terraform-aks-dev-cluster/agentPools/win101]



- List Node Pools
az aks nodepool list --resource-group terraform-aks-dev --cluster-name  terraform-aks-dev-cluster --output table

Name        OsType    KubernetesVersion    VmSize           Count    MaxPods    ProvisioningState    Mode
----------  --------  -------------------  ---------------  -------  ---------  -------------------  ------
linux101    Linux     1.20.7               Standard_DS2_v2  1        30         Succeeded            User
systempool  Linux     1.20.7               Standard_DS2_v2  1        30         Succeeded            System
win101      Windows   1.20.7               Standard_DS2_v2  1        30         Succeeded            User

- List Nodes using Labels
kubectl get nodes -o wide
kubectl get nodes -o wide -l nodepoolos=linux
kubectl get nodes -o wide -l nodepoolos=windows
kubectl get nodes -o wide -l environment=dev

NAME                                 STATUS   ROLES   AGE     VERSION   INTERNAL-IP   EXTERNAL-IP   OS-IMAGE                         KERNEL-VERSION     CONTAINER-RUNTIME
aks-linux101-29775629-vmss000000     Ready    agent   6m3s    v1.20.7   10.240.0.66   <none>        Ubuntu 18.04.5 LTS               5.4.0-1049-azure   containerd://1.4.4+azure
aks-systempool-29775629-vmss000000   Ready    agent   18h     v1.20.7   10.240.0.4    <none>        Ubuntu 18.04.5 LTS               5.4.0-1049-azure   containerd://1.4.4+azure
akswin101000000                      Ready    agent   2m17s   v1.20.7   10.240.0.35   <none>        Windows Server 2019 Datacenter   10.0.17763.2061    docker://20.10.6



terraform destroy
Plan: 0 to add, 0 to change, 7 to destroy.
azuread_group.aks_administrators will be destroyed
azurerm_kubernetes_cluster.aks_cluster will be destroyed
azurerm_kubernetes_cluster_node_pool.linux101 will be destroyed
azurerm_kubernetes_cluster_node_pool.win101 will be destroyed
azurerm_log_analytics_workspace.insights will be destroyed
azurerm_resource_group.aks_rg will be destroyed
random_pet.aksrandom will be destroyed
...
azurerm_kubernetes_cluster.aks_cluster: Destruction complete after 10m36s
...
azurerm_resource_group.aks_rg: Destruction complete after 1m47s
...
Destroy complete! Resources: 7 destroyed.




Warning: Attribute is deprecated
│
│   with azuread_group.aks_administrators,
│   on 06-aks-administrators-azure-ad.tf line 3, in resource "azuread_group" "aks_administrators":
│    3:   name        = "${azurerm_resource_group.aks_rg.name}-cluster-administrators"
│
│ This property has been renamed to `display_name` and will be removed in version 2.0 of the AzureAD provider
╵
╷
│ Warning: Deprecated Attribute
│
│   with azuread_group.aks_administrators,
│   on 06-aks-administrators-azure-ad.tf line 3, in resource "azuread_group" "aks_administrators":
│    3:   name        = "${azurerm_resource_group.aks_rg.name}-cluster-administrators"
│
│ This property has been renamed to `display_name` and will be removed in version 2.0 of the AzureAD provider
╵

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
# Re-Create SAME cluster

re-run terraform apply without changes

terraform apply
random_pet.aksrandom: Creation complete after 0s
azurerm_resource_group.aks_rg: Creation complete after 2s
azuread_group.aks_administrators: Creation complete after 14s
azurerm_log_analytics_workspace.insights: Creation complete after 33s
azurerm_kubernetes_cluster.aks_cluster: Creation complete after 3m37s
azurerm_kubernetes_cluster_node_pool.linux101: Creation complete after 2m40s
azurerm_kubernetes_cluster_node_pool.win101: Creation complete after 5m13s
Apply complete! Resources: 7 added, 0 changed, 0 destroyed.
*** total 4:26 to cluster ***
   7:06 to 1 Linux node
   9:39 to 1 Windows node

kubectl get pods -o wide
Unable to connect to the server: dial tcp: lookup terraform-aks-dev-cluster-258afdfb.hcp.eastus.azmk8s.io on 192.168.4.1:53: server misbehaving

in Safari 1: 
Portal:
confirm Kubernetes cluster
https://portal.azure.com/#@kthomsonair.onmicrosoft.com/resource/subscriptions/cf71d4cd-095a-47ec-bca0-060c571abedf/resourceGroups/terraform-aks-dev/providers/Microsoft.ContainerService/managedClusters/terraform-aks-dev-cluster/overview

check AD: still has 2 users
https://portal.azure.com/#blade/Microsoft_AAD_IAM/ActiveDirectoryMenuBlade/Overview
Kip Thomson  kthomson_air.org#EXT#@kthomsonair.onmicrosoft.com  kthomsonair.onmicrosoft.com
taksadmin1   taksadmin1@kthomsonair.onmicrosoft.com

Safari 1 is my kthomson account/token
Safari 2 is taksadmin1  account/token

for "admin" user
az aks get-credentials --resource-group terraform-aks-dev --name terraform-aks-dev-cluster --admin
(overwrite)
kubectl get nodes
when prompted, log in with the kthomson for Safari 1 browser

*** in admin portal (Safari1), open AD, add taksadmin1 as Member/User 


back in terminal, for "member" user
az aks get-credentials --resource-group terraform-aks-dev --name terraform-aks-dev-cluster --overwrite-existing

# List Kubernetes Nodes
kubectl get nodes
when prompted, log in with the user you want for Safari2 browser
taksadmin1 taksadmin1@kthomsonair.onmicrosoft.com @AKSadmin22

# Change Directory 
cd 24-04-Create-AKS-NodePools-using-Terraform/

# Deploy All Apps
kubectl apply -R -f kube-manifests/

# List Pods
kubectl get pods -o wide

# List Services to get Public IP for each service we deployed 
kubectl get svc

# Access Webserver App (Running on System Nodepool)
http://<public-ip-of-webserver-app>/app1/index.html
http://20.84.3.243/app1/index.html

# Access Java-App (Running on linux101 nodepool)
http://<public-ip-of-java-app>
Username: admin101
Password: password101
http://20.84.4.79

# Access Windows App (Running on win101 nodepool)
http://<public-ip-of-windows-app>
http://20.84.4.186



terraform destroy



=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
# Digress 7/20/21

*** I have used $6.15 of the $150 credit as of this morning ... not much for building and destroying 2 AKS clusters! ***

I used this laptop to access AIR's AKS prod ... had to run get-credentials, etc .. works
but now I can't get terraform to work for MSDN account. 


cd ~/Repos/StackSimplify/Masterclass/azure-aks-kubernetes-masterclass/24-Azure-AKS-Terraform/24-04-Create-AKS-NodePools-using-Terraform/terraform-manifests-aks

terraform plan
│ Error: Backend initialization required, please run "terraform init"
│ Reason: Backend configuration changed for "azurerm"

terraform init
Initializing the backend...
│ Error: Backend configuration changed
│ A change in the backend configuration has been detected, which may require migrating existing state.
│ If you wish to attempt automatic migration of the state, use "terraform init -migrate-state".
│ If you wish to store the current configuration with no changes to the state, use "terraform init -reconfigure".


https://www.terraform.io/docs/cli/commands/index.html
Main commands:
  init          Prepare your working directory for other commands
  validate      Check whether the configuration is valid
  plan          Show changes required by the current configuration
  apply         Create or update infrastructure
  destroy       Destroy previously-created infrastructure


I did remove AKS using "terraform destroy" but terraform should still be able to use the configuation in storage/container/tfstatefile. The backend is the actual Azure account ... the "existing state" would be the contents of the storage/container/tfstatefile.

There IS a local .terraform/terraform.tfstate file ... and it points at the Azure container
    "backend": {
        "type": "azurerm",
        "config": {
            "access_key": null,
            "container_name": "tfstatefiles",
            "key": "terraform.tfstate",
            "resource_group_name": "terraform-storage-rg",
            "storage_account_name": "terraformstorageaksclass",
            "subscription_id": null,
        },


  -reconfigure            Reconfigure the backend, ignoring any saved
                          configuration.

  -migrate-state          Reconfigure the backend, and attempt to migrate any
                          existing state.


I think "destroy" removes all the Azure resources but does NOT update the state file to reflect that. So 

az account list
shows all 5 subscriptions .. with MSDN Enterprise as default

if I open a NEW terminal and do az login to personal account, the login reports only those 2 subs, but az account list still shows all 5





*** Ok, I think I got it: it is b/c I logged into CATO VPN ***
 ... and the Hashicorp CA is not approved
going to a previously working folder/config: (while still on CATO) ***

cd 24-03-Create-AKS-Cluster/terraform-manifests-aks

terraform plan
Acquiring state lock. This may take a few moments...
│ Error: Invalid provider configuration
│
│ Provider "registry.terraform.io/hashicorp/azuread" requires explicit configuration. Add a provider block to the root module and configure the provider's
│ required arguments as described in the provider documentation.
│
╵
╷
│ Error: Error building account: Error getting authenticated object ID: Error parsing json result from the Azure CLI: Error waiting for the Azure CLI: exit status 1: ERROR: Error occurred in request., SSLError: HTTPSConnectionPool(host='graph.windows.net', port=443): Max retries exceeded with url: /e53e4689-2ff4-46b3-a6cb-af78a8dfb38a/me?api-version=1.6 (Caused by SSLError(SSLCertVerificationError(1, '[SSL: CERTIFICATE_VERIFY_FAILED] certificate verify failed: self signed certificate in certificate chain (_ssl.c:1131)')))
│ Certificate verification failed. This typically happens when using Azure CLI behind a proxy that intercepts traffic with a self-signed certificate. Please add this certificate to the trusted CA bundle. More info: https://docs.microsoft.com/cli/azure/use-cli-effectively#work-behind-a-proxy.
│
│   with provider["registry.terraform.io/hashicorp/azurerm"],
│   on 01-main.tf line 41, in provider "azurerm":
│   41: provider "azurerm" {
│
╵
╷
│ Error: getting authenticated object ID: Error parsing json result from the Azure CLI: Error waiting for the Azure CLI: exit status 1: ERROR: Error occurred in request., SSLError: HTTPSConnectionPool(host='graph.windows.net', port=443): Max retries exceeded with url: /e53e4689-2ff4-46b3-a6cb-af78a8dfb38a/me?api-version=1.6 (Caused by SSLError(SSLCertVerificationError(1, '[SSL: CERTIFICATE_VERIFY_FAILED] certificate verify failed: self signed certificate in certificate chain (_ssl.c:1131)')))
│ Certificate verification failed. This typically happens when using Azure CLI behind a proxy that intercepts traffic with a self-signed certificate. Please add this certificate to the trusted CA bundle. More info: https://docs.microsoft.com/cli/azure/use-cli-effectively#work-behind-a-proxy.
│
│   with provider["registry.terraform.io/hashicorp/azuread"],
│   on <empty> line 0:
│   (source code not available)
│
╵

*** Disconnect from CATO: ***

🔥 terraform-manifests-aks (master) 💍 terraform plan

Terraform used the selected providers to generate the following execution plan. Resource actions are indicated with the following symbols:
  + create
 <= read (data resources)

Terraform will perform the following actions:

  # data.azurerm_kubernetes_service_versions.current will be read during apply
  # (config refers to values not yet known)

...

back to the last 24-05 ... and now it works



≈=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
# 196 Provision AKS Cluster with private VNET

StackSimplify/Masterclass/azure-aks-kubernetes-masterclass/24-Azure-AKS-Terraform/24-05-Create-AKS-Cluster-Custom-VNET

copied in the few changes from before .. ran without a glitch

since it is, again, a new cluster, have to update the .kube/config

*** note: this was created as "dev2" not just "dev" ***

ADMIN
az aks get-credentials --resource-group terraform-aks-dev2 --name terraform-aks-dev2-cluster --admin
.kube/config has:
- name: clusterAdmin_terraform-aks-dev_terraform-aks-dev-cluster


# Get Full Cluster Information
az aks show --resource-group terraform-aks-dev2 --name terraform-aks-dev2-cluster
az aks show --resource-group terraform-aks-dev2 --name terraform-aks-dev2-cluster -o table

# Get AKS Cluster Information using kubectl
kubectl cluster-info

# List Kubernetes Nodes
kubectl get nodes

kubectl get all --all-namespaces

USER
az aks get-credentials --resource-group terraform-aks-dev2 --name terraform-aks-dev2-cluster --overwrite-existing
.kube/config has:
- name: clusterUser_terraform-aks-dev_terraform-aks-dev-cluster

kubectl get nodes
To sign in, use a web browser to open the page https://microsoft.com/devicelogin and enter the code E4MSFULC9 to authenticate.

when prompted, log in with the user you want for Safari2 browser, already logged in to portal w/ acct
taksadmin1 taksadmin1@kthomsonair.onmicrosoft.com @AKSadmin22

as expected, gets error b/c this user has not been added to cluster yet:
Error from server (Forbidden): nodes is forbidden: User "taksadmin1@kthomsonair.onmicrosoft.com" cannot list resource "nodes" in API group "" at the cluster scope

go to Portal/active directory/Groups/
open the (trraform created) terraform-aks-dev2-cluster-administrators
click on "Members" and add the user (create at the very beginning in AD)
taksadmin1   taksadmin1@kthomsonair.onmicrosoft.com


Firefox is my pcrp_kthomson account
  terminal can d.host test/prod

Safari window 1 is my kthomson account/token
Kip Thomson  kthomson_air.org#EXT#@kthomsonair.onmicrosoft.com  kthomsonair.onmicrosoft.com
https://portal.azure.com/#home
  access to everything
https://myaccount.microsoft.com/?ref=MeControl   (click on user icon upper right)
  access to Azure account ... everything

Safari window 2 is taksadmin1  account/token
taksadmin1   taksadmin1@kthomsonair.onmicrosoft.com
https://myaccount.microsoft.com
  account is JUST for authentication to AKS services
https://portal.azure.com/#blade/HubsExtension/BrowseAll
  acct has no Azure permissions, no access to the subscription, so can't access anything
  left top hamburger at best goes to Dashboard ... but it is empty

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
# 197 Verify

- List Node Pools
az aks nodepool list --resource-group terraform-aks-dev2 --cluster-name  terraform-aks-dev2-cluster --output table

# List Nodes using Labels
kubectl get nodes -o wide
kubectl get nodes -o wide -l nodepoolos=linux
kubectl get nodes -o wide -l nodepoolos=windows
kubectl get nodes -o wide -l environment=dev2


# Change Directory 
cd 24-05-Create-AKS-Cluster-Custom-VNET/

# Deploy All Apps
kubectl apply -R -f kube-manifests/

# List Pods
kubectl get pods -o wide


and kill it off

terraform destroy


Used $15 to date!!!












=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
# Section 33: Using Terraform and Azure DevOps to Provision AKS Cluster
7/21/21: need to go back to Section 1 to sort out Azure DevOps and Pipelines

full blown cluster with AD and Analytics
REPO: 25-Azure-DevOps-Terraform-Azure-AKS

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
# 199 Install DevOps plugins

carry forward changes from previous work:
01-main.tf
    #storage_account_name  = "terraformstorageaksclass"
02-variables.tf
  default = "East US"
  default = "P@ssw0rd1234abcde"
07-aks-cluster
  drop subnet:
    vnet_subnet_id        = azurerm_subnet.aks-default.id
  parameterize environment
    "environment"   = var.environment
11-virtual-networks.tf
  drop VNET
11-aks-cluster-linux102
  add additional pool

Step 02 ...
even tho the Microsoft plugin has 20K downloads and the "Charles Zipp" has 8K .. Zipp is more recently updated
going with that one
Terraform Build and Release Tasks
https://marketplace.visualstudio.com/items?itemName=charleszipp.azure-pipelines-tasks-terraform


first .. sign in to Azure Devops
https://dev.azure.com --> https://azure.microsoft.com/en-us/services/devops/?nav=min
using kthomson@air.org
I have 2 organizations: AIR and personal (MSDN)
  https://dev.azure.com/American-Institutes-for-Research/
  https://kipthomson.visualstudio.com/
b/c I'm doing this testing with my personal account, use that Organization

this is based on an earlier part of the class I have not done yet, so need to jump back and complete that first
18-Azure-Container-Registry-ACR  (need to connect with Service Principal)
19-Azure-Devops-with-AKS (develop pipeline)
complete all 4 sections resulting in a project "azure-devops-github-aks-app1" in organiztion "aksdemo2"
the plugin needs to be installed in THAT org
Unfortunately, this is an onion ... the pre-reqs for THAT section drags me all the way back to Section 1!!!
I can probably do it fairly easily, but it will take some time

7/21/21: need to go back to Section 1 to sort out Azure DevOps and Pipelines



=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
#
