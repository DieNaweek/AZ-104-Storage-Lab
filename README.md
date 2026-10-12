# AZ-104-Storage-Lab
Hands-on AZ-104 lab covering Azure Storage Accounts, Blob Storage, lifecycle management, SAS tokens, Azure Files, service endpoints, and network access controls. Includes screenshots and practical configuration documentation.
## What I Learned — AZ-104 Storage Lab 

### 1. Azure Storage Accounts

* Created my own storage account and explored the different settings.
* Configured network access to allow only selected networks.
* Added my virtual machine's IPv4 address to the allowed list.

### 2. Lifecycle Management

* Created a lifecycle rule to move blobs to the Cool tier after 30 days without modification.
* Learned how lifecycle management can help reduce storage costs by moving data to a more cost-effective tier.

### 3. Blob Storage and Access Control

* Created a blob container called `data` and uploaded files.
* Explored Hot access tier settings and tested what happens when public access is blocked.
* Generated a read-only Shared Access Signature (SAS) with a limited validity period.
* Used the SAS URL to access a file without making the container public.

### 4. Azure Files

* Created an Azure file share and uploaded a file.
* Explored the file share's settings and management options.

### 5. Networking and Storage Security

* Created a virtual network and subnet.
* Configured a Microsoft.Storage service endpoint.
* Connected the storage account's network rules to my virtual network.
* Removed my previously allowed IP address and tested the access restrictions.

### 💡 My Biggest Takeaway

This lab helped me connect the theory to real Azure configurations. I got hands-on experience with managing storage, controlling access, improving cost efficiency, and securing resources through network restrictions.

One more lab completed, more practical experience gained, and another step forward in my cloud journey! 🚀
