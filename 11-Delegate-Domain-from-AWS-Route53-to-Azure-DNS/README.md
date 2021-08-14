# Delegate Domain to Azure DNS 

## Step-01: Introduction  Lesson 69
- Understand about
  - Domain Registrar
  - DNS Zones
- Learn to delegate a domain from AWS Route53 to Azure DNS by creating DNS Zones in Azure Cloud 

[![Image](https://www.stacksimplify.com/course-images/azure-aks-delegate-domain-to-azure-dns.png "Azure AKS Kubernetes - Masterclass")](https://www.udemy.com/course/aws-eks-kubernetes-masterclass-devops-microservices/?referralCode=257C9AD5B5AF8D12D1E1)


## Step-02: DNS Zones - Create DNS Zone  Lesson 70
- Go to Service -> **DNS Zones**
- **Subscription:** StackSimplify-Paid-Subscription (You need to have a paid subscription for this)
- **Resource Group:** dns-zones
- **Name:** kubeoncloud.com
- **Resource Group Location:** East US
- Click on **Review + Create**

## Step-03: Make a note of Azure Nameservers
- Go to Services -> **DNS Zones** -> **kubeoncloud.com**
- Make a note of Nameservers
```
ns1-02.azure-dns.com.
ns2-02.azure-dns.net.
ns3-02.azure-dns.org.
ns4-02.azure-dns.info.
```

## Step-04: Update Nameservers at your Domain provider (Mine is AWS)
- **Verify before updation**
```
nslookup -type=SOA andrewthomson.org
nslookup -type=NS andrewthomson.org
```
- Go to AWS Route53 (This is my Domain Provider)
- Go to Services -> Route53 -> Registered Domains -> kubeoncloud.com
- Click on **Add or edit name servers**
- Update Azure Name servers here and click on **Update**
- Click on **Hosted Zones**
- Delete the hosted zone with name **kubeoncloud.com**
- **Verify after updation**
```
nslookup -type=SOA kubeoncloud.com 8.8.8.8
nslookup -type=NS kubeoncloud.com 8.8.8.8
```
