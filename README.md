# Microsoft Entra ID Identity & Access Management Lab

## Overview
A hands-on lab where I built and configured a Microsoft Entra ID tenant 
from scratch to practice identity and access management (IAM) concepts — 
core skills for IT support, sysadmin, and cloud administration roles.

## Environment
- Platform: Microsoft Entra ID (Azure)
- Tenant: self-provisioned, personally owned (Global Administrator)
- Tools: Microsoft Entra Admin Center

## What I Built

### 1. Tenant Creation
 <img width="1710" height="786" alt="Tenant Overview" src="https://github.com/user-attachments/assets/5ce2cf35-28be-405c-9af8-69c27eea2a80" />


Created a dedicated Entra ID tenant (JBrownEntraLab) to have full 
administrative control for hands-on practice, separate from any 
organizational directory.

### 2. User Management
<img width="1709" height="907" alt="Screenshot one users" src="https://github.com/user-attachments/assets/636cd6dc-0164-4bfc-b5e0-221eca295fb7" />

Created 4 test users to simulate a small organization's identity structure.
- Why: understanding user provisioning is foundational to IAM — every 
  access decision starts with a verified identity.

### 3. Group Management
 <img width="2962" height="1642" alt="IT support group 2" src="https://github.com/user-attachments/assets/131b2ab0-3d90-404a-8c5a-65d3dfc18e3b" />

 <img width="1710" height="860" alt="Sales Team group 2" src="https://github.com/user-attachments/assets/37a00124-f076-483c-9d38-320382779d70" />

 <img width="2880" height="1892" alt="Groups Overview" src="https://github.com/user-attachments/assets/f523149e-1336-42d3-99c4-9b362bf51107" />

Created two security groups reflecting real departmental structure:
- **IT-Support** — used for assigning IT department software licenses, 
  internal service desk application access, and core IT distribution lists.
- **Sales-Team** — [paste whatever description you wrote for that one]
- Why: groups let you manage access at scale instead of per-user, which 
  is how real organizations handle permissions.

### 4. Role Assignment
<img width="1709" height="763" alt="Untitled" src="https://github.com/user-attachments/assets/7a9e7794-e8b2-4ef3-b97e-504cf1ec5d38" />
Assigned the Helpdesk Administrator role to a test user (Alex Chen) 
instead of Global Administrator.
- Why: This follows the principle of least privilege, giving a user 
  only the access their actual job requires (resetting passwords, 
  handling basic account issues) rather than full administrative 
  control over the tenant. If that account were ever compromised, 
  the damage an attacker could do is limited to helpdesk-level actions, 
  not the entire environment.

## Key Takeaways
Working through this hands-on gave me a much clearer picture of how 
identity management supports real IT/security operations — creating 
users, assigning them to the correct group, and moving them between 
groups when roles change are everyday tasks for an IT or security team, 
not just abstract concepts. Being able to auto-generate secure passwords 
rather than manually creating them also showed me how identity platforms 
build good security practice into the workflow by default. The initial 
setup (authenticator app, MFA) was a new experience for me as I'm not 
deeply familiar with the Windows/Microsoft ecosystem, which was a good 
reminder of what I still need to get comfortable with heading into 
entry-level IT roles.

## Next Steps
- Planning to explore Conditional Access policies and MFA enforcement
