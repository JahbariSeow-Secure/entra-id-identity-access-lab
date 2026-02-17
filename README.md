# Microsoft Entra ID – Identity & Access Management Lab

This lab demonstrates hands-on skills in **Microsoft Entra ID**, including **Privileged Identity Management (PIM)**, **Conditional Access**, **Entitlement Management**, and **Access Reviews**.  

The lab simulates enterprise identity and access management to showcase **Zero Trust principles**, **least privilege access**, and **identity governance**.

---

## Users & Groups

- Created users simulating employees, admins, and external vendors  
- Configured groups such as `HR-Users`, `IT-Admins`, `Finance-Users`, and `All-Employees`  
- Assigned users to groups according to roles for proper access management  

**Business Problem Solved:**  
- Ensures proper user segmentation and access control based on roles  
- Reduces risk of unauthorized access by organizing users into least-privilege groups  

![Users and Groups](screenshots/01-users.png)  
*Overview of user accounts created for the lab environment.*

![Groups Membership](screenshots/02-groups-membership.png)  
*Shows group memberships and assignments for access control.* 

---

## Privileged Identity Management (PIM)

- Configured **eligible role assignments** requiring MFA and time-bound activation  
- Roles are activated **just-in-time** to enforce least privilege principles  
- Monitored and audited **role activations** for compliance and security  

**Business Problem Solved:**  
- Reduces risk of **over-privileged accounts** and insider threats  
- Ensures **temporary elevated access** only when needed, minimizing attack surface  
- Provides audit trails for **compliance and regulatory requirements**  
- Aligns with **least privilege and Zero Trust principles**, giving secure access without permanent admin rights  

![PIM Overview](screenshots/pim-overview.png)  
*High-level view of PIM dashboard showing eligible roles and assignments.*

![Eligible Role Assignment](screenshots/03-pim-eligible-role.png)  
*Example of a role assigned as eligible, requiring activation before use.*

![Role Settings](screenshots/04-pim-role-settings.png)  
*Configuration settings for PIM roles, including MFA and activation duration.*

![Role Activated](screenshots/05-pim-role-activated.png)  
*Demonstration of a role activated just-in-time for temporary access.*

---

## Conditional Access

- Implemented **Conditional Access policies** enforcing MFA for all users  
- Scoped policies to balance security and usability, preventing administrative lockouts  
- Applied **Zero Trust principles** to secure cloud applications and sensitive resources  

**Business Problem Solved:**  
- Reduces risk of **unauthorized access** to corporate systems and sensitive data  
- Enforces compliance requirements for multi-factor authentication  
- Protects the organization from phishing, credential theft, and insider threats  
- Ensures only the right users from trusted devices/locations can access critical applications  

![Conditional Access Blade](screenshots/06-conditional-access-blade.png)  
*Policy overview and assignment scope for targeted users or groups.*

![Add New Policy](screenshots/06-conditional-access-new.png)  
*Creating a new Conditional Access policy in Microsoft Entra ID.*

![Policy Settings](screenshots/06-conditional-access-settings.png)  
*Detailed policy settings including conditions, controls, and session settings.*

---

## Entitlement Management (Access Packages)

- Built **Access Packages** to automate onboarding for HR groups and other departments  
- Configured **time-bound access** and **approval workflows** for governance  

**Business Problem Solved:**  
- Streamlines access requests and approvals  
- Ensures compliance with least-privilege access and governance policies  

![Entitlement Management Blade](screenshots/07-access-package-blade.png)  
*Access Package overview blade showing available packages and workflows.*

![New Access Package](screenshots/07-access-package-new.png)  
*Creating a new access package with approvals and time-bound access.*

---

## Access Reviews

- Created **resource access reviews** to periodically validate user access  
- Ensured **least privilege** and compliance through scheduled reviews  

**Business Problem Solved:**  
- Detects and removes unnecessary access to sensitive resources  
- Helps maintain ongoing compliance and reduce security risk  

![Access Review Overview](screenshots/08-access-review.png)  
*Overview of access review policies and their status.*

![New Access Review](screenshots/08-access-review-new.png)  
*Creating a new access review for a specific group or application.*

---

## Technologies Used

- Microsoft Entra ID / Azure AD  
- Privileged Identity Management (PIM)  
- Conditional Access  
- Entitlement Management & Access Packa
