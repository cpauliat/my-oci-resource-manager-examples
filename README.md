# my-oci-resource-manager-examples

my examples of OCI Resource Manager Stacks (Terraform as a service in Oracle Cloud Infrastructure)

### 01_OCI_demo_vcn_OL7_instance.zip

```
Summary: basic VCN + basic Oracle Linux 7 compute instance for Oracle Linux 7

Details:
- 1 VCN with 1 public regional subnet + 1 internet gateway + 1 route table + 1 security list
- 1 compute instance Oracle Linux 7 (latest image) with public IP and Cloud-init post provisioning actions
- parameters asked by the Resource Manager Stack:
    - for network: VCN name, VCN CIDR, public subnet CIDR, IP range authorized for SSH
    - for compute instance: availability domain, shape, SSH public key


Last update: April 13, 2022
```
