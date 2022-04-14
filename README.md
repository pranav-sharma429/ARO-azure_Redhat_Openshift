# Azure Red hat OpenShift Container Platform  Cloud Infrastructure Auomtation 
### - by Pranav Sharma, Principal Solutions Architect - DevOps Consulting
Ansible Playbook Module structure that configures a complete OpenShift 4.x Cluster latest version with complete configuration on Azure Cloud with all services  

## Architecture
### UseCase - Provisioning+Compliance+Automation+Orchrestration+Apps Deployment
 ![picture](docs/imgs/aro.png)

### Following are the current feature set for a ARO Provisioning
1. Creating Resource group infrastructure on Azure Cloud
2. Creating required Virtual Network and Subnets for VMs
3. Creating Network Security Groups with required port allow/deny rules
4.
5.
6.
7.

Pre-requisites:
1. Ansible v2.9 or later installed
2. Azure Cloud API or CLI Key Credentials embedded to system
## Preparations

1. Create a Ansible Creds file in `~/.azure/credentials` following below format:
```
[default]
subscription_id=<your-subscription_id>
client_id=<security-principal-appid>
secret=<security-principal-password>
tenant=<security-principal-tenant>
```
```
## Running the Installation

```
#git clone git@github.com:pranav-sharma429/ARO-azure_Redhat_Openshift.git
```

