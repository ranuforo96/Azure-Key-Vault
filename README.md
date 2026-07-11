# Azure-Key-Vault
Creating a key vault
I logged into my Azure account through the Azure Portal
<img width="1920" height="1036" alt="image" src="https://github.com/user-attachments/assets/c4c3fb0a-9131-4640-b31e-39ab6c2af5fb" />
I clicked on the "All Services" menu item on the left-hand side of the portal.
<img width="1920" height="1030" alt="image" src="https://github.com/user-attachments/assets/afd31c67-7b3c-4c59-9787-79e41cd1210f" />
 I typed the keyword "Vault" into the search bar and selected the Key Vault service from the results.
<img width="1599" height="738" alt="image" src="https://github.com/user-attachments/assets/f4186081-5b7f-4eb2-8731-9e92c9f8db2c" />
I clicked the "Create" button to begin the creation process.
<img width="1599" height="738" alt="image" src="https://github.com/user-attachments/assets/507d662f-65ad-4274-a00f-9c0ee2f1359c" />
Next steps are just filling out basic information:
I selected the Azure subscription under which the Key Vault would be created and billed.

Then I selected the existing resource group (or created a new one) to house the Key Vault.
<img width="1599" height="738" alt="image" src="https://github.com/user-attachments/assets/1c76e873-5e8d-418e-895b-869742bd6d58" />
I entered a unique name for the Key Vault (e.g., mykeyvaultelp), making sure it was unique across Azure.
<img width="1599" height="738" alt="image" src="https://github.com/user-attachments/assets/57c2c91c-f91f-4a9d-8626-eb715365e74e" />
 I chose the appropriate geographic region for the Key Vault, selecting "East US."

 Afterward, I selected the pricing tier that fit my needs, choosing between "Standard" and "Premium" (Premium supports physical HSM-backed keys).
 <img width="1599" height="738" alt="image" src="https://github.com/user-attachments/assets/16cf5735-1a27-4fe2-84ce-b8c7d2f0c142" />
 Then, from here we configure the Access Configuration, which consists of the Permission Model and the Resource Access: 
 Permission Model - I set the permission model for the Key Vault, choosing between Azure role-based access control (RBAC) or vault access policies.
 <img width="1599" height="738" alt="image" src="https://github.com/user-attachments/assets/8f4323b0-724b-42bd-a82d-4e8e5d7df625" />
Resource Access - I configured resource access settings to allow specific Azure services to interact with the Key Vault, enabling options such as Azure Virtual Machines to retrieve certificates stored as secrets, Azure Resource Manager to retrieve secrets for template deployment, and Azure Disk Encryption to access keys for encrypting VM disks, as needed.
 <img width="1599" height="738" alt="image" src="https://github.com/user-attachments/assets/ee13af4a-4534-4d26-821a-02b609586762" />
Configure the Networking Tab – I specified how the Key Vault could be accessed, choosing between public access from all networks or restricting access to selected virtual networks and IP addresses, and configured private endpoint connections if needed for added security.
<img width="1599" height="738" alt="image" src="https://github.com/user-attachments/assets/78e65945-433e-4005-b5c2-871e4ae31599" />
I then clicked on Review and create tab.
<img width="1599" height="738" alt="image" src="https://github.com/user-attachments/assets/ff59b924-ccdf-4011-a693-b32c21732b13" />
I reviewed all the configuration settings across the Basics, Access Configuration, and Networking tabs to confirm everything was correct, then clicked "Create" to provision the Key Vault.
<img width="1599" height="738" alt="image" src="https://github.com/user-attachments/assets/3437f93e-20d9-4c4d-90fb-b4adc814a8e6" />
