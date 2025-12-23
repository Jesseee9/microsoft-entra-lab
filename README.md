# microsoft-entra-lab
Hands-on documentation of Microsoft Entra ID lab. Covers user/group management, license and role assignments, password protection, conditional access policies, and What-If analysis for cloud identity management.
# Microsoft Applied Skills: Get Started with Identities and Access using Microsoft Entra

## Overview
This project documents my hands-on work completing the **Microsoft Applied Skills lab** focused on **identities and access management using Microsoft Entra ID**.  

The lab helped me learn how to:  
- Create, configure, and manage users and groups  
- Assign roles and licenses  
- Configure basic password protection and self-service password reset (SSPR)  
- Use conditional access policies and What-If analysis to understand policy enforcement  

This project demonstrates **practical, hands-on experience with cloud identity management**, which is a key foundational skill for Cloud Engineering and IT roles.

---

## Objectives
- Perform **basic user and group management** tasks in Microsoft Entra ID  
- Assign licenses and roles to users  
- Invite external users and configure guest access  
- Configure and document **password protection** and **authentication method policies**  
- Create security groups, assign roles, and add members/owners  
- Use **conditional access policies** and **What-If analysis** to validate policy application  

---

## Tasks Completed
### 1. User Management
- Created users: Ben Smith, assigned job title and department  
- Assigned **Office 365 E5 license** to Ben Smith  
- Assigned **Billing Administrator role** to Lynn Robbins  
- Invited external user: Arlen Hoff  

### 2. Group Management
- Created Security Group: `Tech 1`  
- Assigned **Reports Reader role** to the group  
- Added **Alex Wilbur** as a member of Tech 1  
- Added **Alex Wilbur** as an owner of the **SSPR Security Group**  
- Added **Megan Bowen** as a member of the group  

### 3. Password Protection
- Configured **Number of methods required for password reset**: 1  
- Documented other authentication methods as **No** (not shown in portal)  

### 4. Named Locations
- Documented named locations for conditional access: **Algeria**, **Sweden**  

### 5. Conditional Access Policies
- Used **What-If analysis** to determine policy application for a scenario user (Diego Siciliani)  
- Documented which policies **applied** and their **states**:  
  | Policy | Applies | State |
  |--------|--------|-------|
  | Policy 1 | No | On |
  | Policy 2 | Yes | On |
  | Policy 3 | Yes | Report-only |
  | Policy 4 | Yes | Report-only |
- Documented **assigned users** for each policy:  
  | Policy | Users |
  |--------|-------|
  | Policy 1 | Alex Wilbur |
  | Policy 2 | Diego Siciliani |
  | Policy 3 | All users |
  | Policy 4 | All users |

---

## Key Learnings
- How to manage **users, groups, and roles** in Microsoft Entra ID  
- How to perform **hands-on conditional access analysis**  
- Understanding the difference between **policy configuration** and **actual policy application**  
- Best practices for **documenting cloud identity setups** for audit, training, or resume purposes  

---

## Conclusion
This lab reinforced my **cloud identity management skills**, which are essential for IT support, cloud engineering, and AI-ready cloud roles.  
The project demonstrates **hands-on applied skills**, ready to include in my resume or portfolio.

---<img width="991" height="638" alt="image" src="https://github.com/user-attachments/assets/42083a26-b548-4d7d-bcdd-def35e588a27" />
