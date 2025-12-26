# Week 1 – Windows Server AD & GPO Lab

## Project Overview
This lab demonstrates hands-on experience in setting up an enterprise-style Active Directory environment using VMware. The goal was to implement organizational units (OUs), role-based Group Policy Objects (GPOs), and domain-joined clients to enforce company policies and user permissions.

---

## Environment
- VMware Workstation
- Windows Server 2016 (Domain Controller)
- Windows 10 (Client Machine)

---

## Tasks Completed

### 1. Virtual Machine Setup
- Created two VMs:
  - Windows Server 2016 (Server)
  - Windows 10 (Client)
- Configured networking for domain communication

### 2. Server Role Installation & Organizational Setup
- Installed:
  - Active Directory Domain Services (AD DS)
  - Domain Name System (DNS)
  - Dynamic Host Configuration Protocol (DHCP)
- Created an OU structure for 3 locations, each with HR, IT, and Admin departments
- Applied unique desktop wallpapers for each department
- Configured GPOs:
  - IT → Full access (Read/Write/Delete)
  - HR → Read & Write only
  - Admin → Read-only
- Created users per department with role-based permissions:
  - Administrator → Full access
  - Registered User → Change desktop & Remote Desktop settings
  - Guest → Login only

### 3. Domain Registration
- Joined Windows 10 client to the Active Directory domain

### 4. Validation & Testing
- Verified:
  - GPOs applied correctly
  - Permissions enforced per role
  - Department-specific wallpapers appear
- Documented evidence in Word file

---

## Key Skills Demonstrated
- Windows Server Administration
- Active Directory & OU structure design
- GPO management and role-based access control
- VMware virtual machine setup
- User permissions & policy enforcement
- Documentation of IT projects

---

## 📂 Proof
All screenshots and detailed implementation steps are documented in the attached Word file:  
`Week1-AD-GPO-Lab.docx`

---

## 💬 How I Explain This in Interviews
> “I designed and implemented an enterprise-style Active Directory lab with Windows Server 2016, configured OU structures, department-based GPOs, and joined client machines to the domain. This lab taught me how to enforce permissions, manage policies, and troubleshoot domain-related issues.”
