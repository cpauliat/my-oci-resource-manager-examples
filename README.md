# my-oci-resource-manager-examples

my examples of OCI Resource Manager Stacks (Terraform as a service in Oracle Cloud Infrastructure)

### 01_OCI_demo_vcn_OL7_instance.zip

```
Summary: basic VCN + basic Oracle Linux 7 compute instance

Details:
- 1 VCN with 1 public regional subnet + 1 internet gateway + 1 route table + 1 security list
- 1 compute instance Oracle Linux 7 (latest image) with public IP and Cloud-init post provisioning actions
- parameters asked by the Resource Manager Stack:
    - for network: VCN name, VCN CIDR, public subnet CIDR, public IP address CIDR block authorized for SSH
    - for compute instance: availability domain, shape, instance name, instance hostname, SSH public key


Last update: April 13, 2022
```

### 10_OCI_demo_vcn_win2016_win2019_instance.zip

```
Summary: basic VCN + basic Microsoft Windows Server 2016 or 2019 compute instance

Details:
- 1 VCN with 1 public regional subnet + 1 internet gateway + 1 route table + 1 security list
- 1 compute instance Microsoft Windows Server 2016 or 2019 (latest image) with public IP and Cloud-init post provisioning actions
- parameters asked by the Resource Manager Stack:
    - for network: VCN name, VCN CIDR, public subnet CIDR, public IP address CIDR block authorized for RDP
    - for compute instance: availability domain, shape, instance name, instance hostname, OS version (2016 or 2019)


Last update: April 13, 2022
```
