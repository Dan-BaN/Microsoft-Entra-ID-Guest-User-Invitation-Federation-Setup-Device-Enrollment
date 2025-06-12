# 🔐 Microsoft Entra ID: Guest User Invitation, Federation Setup & Device Enrollment

This project showcases real-world administrative tasks performed within Microsoft Entra ID (formerly Azure Active Directory), focusing on:

- Inviting and managing external (B2B) users
- Configuring identity federation with Google
- Registering and managing Windows devices in Entra ID

---

## 🎯 Objective

To simulate identity lifecycle operations and external collaboration using Microsoft Entra ID, with a focus on:

- Secure onboarding of external users
- Federation with a third-party identity provider (Google)
- Device enrollment and verification using `dsregcmd`

---

## ✅ Tasks Performed

### 1. **External Guest User Invitation**
- Invited external users by email, set display names, and customized messages.
- Verified successful invitation via the guest list in Entra ID with status "Guest - Invited".
- Ensured delivery and acceptance of invitations through Microsoft-branded email links.

### 2. **Federation Setup with Google**
- Used Google Cloud Console to create an OAuth client for federation.
- Configured Google as a federated IdP in Entra, allowing login with Google accounts.
- Tested federation with designated test users and verified successful IdP integration.
- Confirmed Google and Microsoft were both active identity providers.

### 3. **Device Enrollment to Entra ID**
- Connected a Windows 10 Pro device to Entra via **Access work or school** settings.
- Verified device registration using `dsregcmd /status` (WorkplaceJoined = YES).
- Checked Entra ID > Devices to ensure correct device registration under user identity.

---

## 🛠️ Tools & Services Used

| Tool                     | Purpose                                      |
|--------------------------|----------------------------------------------|
| Microsoft Entra ID       | Identity and access management               |
| Azure Portal             | Configuration and user/device visibility     |
| Google Cloud Console     | Created OAuth client for federation          |
| Windows 10 Pro           | Device used for Entra enrollment             |
| dsregcmd (CMD)           | Verified device registration status          |

---

## 📸 Screenshots

All actions were documented with step-by-step screenshots and descriptions.

You can view the complete lab walkthrough in the attached PDF:  
📄 [EntraID_Lab_With_Descriptions.pdf](./EntraID_Lab_With_Descriptions.pdf)

---

## 🚀 Outcome

- Demonstrated ability to securely invite and manage external collaborators
- Configured and validated identity federation with an external IdP
- Enrolled a Windows device to Entra ID and confirmed organizational registration

---

## 🧠 Learnings

- Hands-on experience with federated authentication and OAuth client setup
- End-to-end user lifecycle management (Guest → Federation → Device)
- Troubleshooting device join issues and understanding MDM/Workplace Join mechanics

---

## 🔗 Relevant Topics

- Azure AD B2B Collaboration  
- Microsoft Entra Federation  
- Device Identity & Registration  
- Modern Authentication  
