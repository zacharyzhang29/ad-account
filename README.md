<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>Active Directory Account Management</h1>
This repository demonstrates various use cases and examples for managing user accounts in Active Directory (AD). It provides step-by-step instructions on common tasks, such as account lockouts, password resets, account enabling/disabling, and log observations.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>Use Cases</h2>

- Account Lockouts
  - How to configure account lockout policies via Group Policy.
  - Simulating account lockouts by attempting multiple failed login attempts.
  - Unlocking a locked account and resetting the password.

- Enabling and Disabling Accounts
  - Disabling and enabling a user account within Active Directory.
  - Observing the behavior and error messages when attempting to log in with a disabled account.

- Log Observations
  - How to observe and analyze security logs from both the Domain Controller and client machine.
  - Identifying failed login attempts, account lockouts, and other relevant events in the logs.

<h2>Instructions</h2>

**1. Getting Started**

- Log in to the Domain Controller (dc-1) using an administrator account.
- Ensure you have a user account created in Active Directory for testing purposes.

**2. Configuring Account Lockout Policies**




