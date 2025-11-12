# microsoft365admin
A general overview of Microsoft 365 Admin Center
Video Link to watch the lab project: https://youtu.be/-N1-j0XNxwc

## **Microsoft 365 Administration Home Lab Project**

### **Objective**

To demonstrate practical skills in managing a Microsoft 365 environment, including user and group administration, collaboration setup, licensing, Exchange configuration, device management, and security compliance using the Microsoft 365 Admin Center, Azure AD, and Intune.

---

### **Environment Setup**

* **Platform:** Microsoft 365 E5 Developer Subscription
* **Tools Used:** Microsoft 365 Admin Center, Entra ID, Intune (Endpoint Manager), Exchange Admin Center, and Teams
* **Lab Infrastructure:**

  * Local virtual machine joined to Azure AD
  * Multiple test user accounts simulating employees and managers

---

### **Phase 1: User & Group Management**

1. **Created test users** such as *Employee*, *Intern*, and *Manager* within the Microsoft 365 Admin Center.
2. **Assigned administrative role** *Global admin* to a specific user to simulate IT permissions.
3. **Reset passwords and managed MFA settings** to implement account security measures.
4. **Configured Self-Service Password Reset (SSPR)** in Azure AD, enabling users to reset their own passwords securely.
5. **Created Microsoft 365 and Security Groups** for organizing users by department and managing access to resources.

---

### **Phase 2: Collaboration Setup**

1. **Created Teams** for each department (e.g., IT, HR, Sales) to facilitate internal communication.
2. **Tested file permission levels** (View/Edit/Owner) to verify access control policies.

---

### **Phase 3: Licensing & App Management**

1. **Assigned and removed licenses** for Microsoft Teams, Exchange Online, and SharePoint to simulate provisioning and deprovisioning workflows.
2. **Verified service access** for each user to confirm successful license application and service availability.

---

### **Phase 4: Email & Exchange Tasks**

1. **Created and managed user mailboxes**, ensuring automatic mailbox creation during user provisioning.
2. **Created shared mailboxes and delegated access** for team-based communication scenarios.
3. **Set up mailbox rules and performed message traces** for troubleshooting email delivery issues.

---

### **Phase 5: Device & Endpoint Management**

1. **Enrolled a virtual machine in Intune (MDM/MAM)** to test device compliance.
2. **Joined the device to Azure AD** for centralized identity and access control.
3. **Pushed compliance policies** enforcing password complexity, encryption, and screen lock to maintain endpoint security.

---

### **Phase 6: Security & Compliance**

1. **Configured Conditional Access policies** to enforce MFA for specific users or locations.
2. **Reviewed audit logs and sign-in logs** to monitor user activity and ensure compliance posture.

---

### **Outcome**

Successfully simulated a Microsoft 365 production environment with full administrative control, demonstrating skills in:

* User identity and access management
* License provisioning
* Collaboration and email configuration
* Device compliance management
* Security policy enforcement

---

### **Key Skills Demonstrated**

* Microsoft 365 Administration
* Entra ID / Azure Active Directory (AAD)
* Exchange Online & Teams Administration
* Intune (Endpoint Manager)
* Conditional Access Policies
* Identity, Security, and Compliance Management

---
