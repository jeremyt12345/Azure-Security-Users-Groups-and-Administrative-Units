# Azure-Security-Users-Groups-and-Administrative-Units
Understanding Users, Groups, and Administrative Units within a Mad Hat Labs 


<img width="1117" height="556" alt="image" src="https://github.com/user-attachments/assets/94aa52bb-5eb9-4e59-9f50-f7e2f6db6080" />



Users
The base identity object. Carries attributes (display name, UPN, email, job title, manager, groups, licenses) plus a permanent object ID that never changes even if other attributes do. Two types:

Member — native to the tenant, broad default permissions (can read other users, manage own profile/password, register apps)
Guest — invited from outside via B2B, signs in with their own org's credentials, restricted permissions by default. Even a personal Microsoft account counts as a guest in your tenant.

Also: users are either cloud-only (created directly in Entra) or synced from on-prem AD via Entra Connect — the latter is common in large legacy orgs and complicates things like password resets.

Groups
How access scales without managing users one-by-one — grant access to the group once, add/remove members, access follows automatically. Two types:

Security groups — control access (resources, apps, licenses, Conditional Access, roles); can hold users, devices, service principals, even other groups (nesting)
Microsoft 365 groups — built for collaboration (mailbox, SharePoint, Teams); users only, no devices/service principals



<img width="1038" height="273" alt="image" src="https://github.com/user-attachments/assets/02f89b8e-6029-436a-a1c5-4d3da9546d7c" />


Answer Below


<img width="1912" height="914" alt="image" src="https://github.com/user-attachments/assets/8dd9d7fe-f931-42cc-8224-2e7d16e363ab" />



Question 2

<img width="1080" height="287" alt="image" src="https://github.com/user-attachments/assets/b194a8c9-b820-4eb7-98e2-5a5ffd730238" />

Answer


<img width="1912" height="914" alt="image" src="https://github.com/user-attachments/assets/1253e7ef-cf4d-4901-a5ec-1ec215ababb2" />



