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
[Screenshot: tenant overview] <img width="1710" height="786" alt="Tenant Overview" src="https://github.com/user-attachments/assets/5ce2cf35-28be-405c-9af8-69c27eea2a80" />


Created a dedicated Entra ID tenant (JBrownEntraLab) to have full 
administrative control for hands-on practice, separate from any 
organizational directory.

### 2. User Management
[Screenshot: users list] <img width="1709" height="907" alt="Screenshot one users" src="https://github.com/user-attachments/assets/636cd6dc-0164-4bfc-b5e0-221eca295fb7" />

Created 4 test users to simulate a small organization's identity structure.
- Why: understanding user provisioning is foundational to IAM — every 
  access decision starts with a verified identity.

### 3. Group Management
[Screenshot: IT-Support group overview] <img width="2962" height="1642" alt="IT support group 2" src="https://github.com/user-attachments/assets/131b2ab0-3d90-404a-8c5a-65d3dfc18e3b" />

[Screenshot: Sales-Team group overview] <img width="1710" height="860" alt="Sales Team group 2" src="https://github.com/user-attachments/assets/37a00124-f076-483c-9d38-320382779d70" />

[Screenshot: All groups list] <img width="2880" height="1892" alt="Groups Overview" src="https://github.com/user-attachments/assets/f523149e-1336-42d3-99c4-9b362bf51107" />

Created two security groups reflecting real departmental structure:
- **IT-Support** — used for assigning IT department software licenses, 
  internal service desk application access, and core IT distribution lists.
- **Sales-Team** — [paste whatever description you wrote for that one]
- Why: groups let you manage access at scale instead of per-user, which 
  is how real organizations handle permissions.

### 4. Role Assignment
[Screenshot: role assignment page]
Assigned [role name] to [user/group].
- Why: role-based access control (RBAC) follows least-privilege — giving 
  only the access needed, not more.

## Key Takeaways
- [Write 2-3 sentences in your own words about what you understood better 
  after doing this hands-on vs. just reading about it]

## Next Steps
- Planning to explore Conditional Access policies and MFA enforcement
