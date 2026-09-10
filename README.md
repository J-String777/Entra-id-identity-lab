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
[Screenshot: tenant overview page showing domain name]
Created a dedicated Entra ID tenant to have full administrative control 
for hands-on practice, separate from any organizational directory.

### 2. User Management
[Screenshot: users list]
Created [X] test users to simulate a small organization's identity structure.
- Why: understanding user provisioning is foundational to IAM — every 
  access decision starts with a verified identity.

### 3. Group Management
[Screenshot: group created, members assigned]
Created a [security group name] and assigned users to it.
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
