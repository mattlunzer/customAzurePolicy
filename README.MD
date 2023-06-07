# Custom Azure Policies

The following custom polices and their use case in this folder are as follows;

- [auditHyrbidUseBenefit.json](https://github.com/mattlunzer/customAzurePolicy/blob/master/auditHyrbidUseBenefit.json) - 
This policy audits all Windows Servers for the Azure Hybrid Use Benefit. If they are configured with Hybrid Use Benefit, their identified as compliant, if not, they'll be identified as non-compliant. 

- [blcokUbuntuEndOfLifeOS.json](https://github.com/mattlunzer/customAzurePolicy/blob/master/blockUbuntuEndOfLifeOS.json) - 
This policy blocks all Ubuntu 14.04, 16.04 and 18.04 Gen1, Gen2 LTS Marketplace VMs from being deployed. Not tested w/custom images.