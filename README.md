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

- Open the Group Policy Management Console (GPMC) and configure the Account Lockout Policy to lock the account after 5 failed login attempts.
- Test by attempting 6 failed logins with a bad password.

<img width="448" alt="Screenshot 2025-01-23 at 6 43 36 PM" src="https://github.com/user-attachments/assets/0d424068-0be0-4580-be80-cc4abc554b0e" />
<img width="395" alt="Screenshot 2025-01-23 at 6 45 12 PM" src="https://github.com/user-attachments/assets/f105c6d8-ae9c-4703-82d6-1704a238d0be" />
<img width="791" alt="Screenshot 2025-01-23 at 6 45 33 PM" src="https://github.com/user-attachments/assets/32bc91e8-8b5f-4fbb-98a2-6ef4ea6ad1b1" />
<img width="859" alt="Screenshot 2025-01-23 at 6 46 31 PM" src="https://github.com/user-attachments/assets/8e1203c0-dcf7-4c9a-b53a-89bbf340de0f" />
<img width="436" alt="Screenshot 2025-01-23 at 6 47 23 PM" src="https://github.com/user-attachments/assets/9572d678-b0b3-433c-b281-fcb3735a1cbb" />




