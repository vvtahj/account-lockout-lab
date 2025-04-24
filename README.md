<p align="center">
<img src="https://github.com/user-attachments/assets/7832956f-f6ca-4ac1-93e3-703b9d3d7e57" 
</p>





# 🔐 Group Policy: Password Policy & Lockout Settings

In this lab, I used Group Policy to strengthen account security across a domain. I enforced strong password rules and set limits on failed login attempts to block unauthorized access and protect users across the network.

---


🎯 **Main Focus**  
✅ Enforce secure password policies  
✅ Limit failed login attempts  
✅ Simulate account lockouts and recovery  

## 🧷 Scenario

📍 **Organization Issue:**  
User accounts were being compromised due to weak password rules and unlimited login attempts. IT leadership tasked me with strengthening password security and preventing brute-force access in a Windows Server domain environment.

---

## 🧰 What Tools Did I Use?
- 🖥️ Windows Server (Domain Controller)
- 🧑‍💻 Group Policy Management Console (GPMC)
- 🔐 Active Directory (ADUC)
- 🕵️ Event Viewer (to see what really happened behind the scenes)

---

## ✅ What Did I Actually Do?

| Task                                | Purpose                                    |
|-------------------------------------|---------------------------------------------|
| Created login rules using GPO       | To control password & lockout behavior      |
| Set lockout after failed logins     | To stop hackers from guessing passwords     |
| Tested account lockouts             | By typing the wrong password on purpose     |
| Unlocked accounts as admin          | To restore access when someone was locked   |
| Reset user passwords                | For accounts that needed a fresh start      |

---

## 🔐 Why This Matters

🔒 People can’t just keep guessing passwords  
🧠 Even if they forget it, we can help reset it  
👨‍💻 As the admin, I can protect and manage all logins in one place  

This is how real companies prevent unauthorized access and make sure users follow strong password rules.

---

## 🖼️ Screenshots  
*(Insert screenshots showing the GPO settings, lockout screen, account reset, Event Viewer logs, etc.)*




## 🔐 Account Lockout & Password Policy Lab

This lab demonstrates how to configure account lockout settings and password policies using Group Policy Management, and how to reset or unlock user accounts via Active Directory.

<p align="center">
  <img src="https://github.com/user-attachments/assets/c84f3748-5725-4d1f-8627-bb4c200a621a" width="700"/>
  <figcaption><strong>Figure 1:</strong> Launching Group Policy Management Console (gpmc.msc) using the Windows Run dialog. This tool is used to manage domain-wide group policies.</figcaption>
</p>


<p align="center">
  <img src="https://github.com/user-attachments/assets/e46607cf-2c4b-4b6e-a8f9-db2fd183a8d5" width="850"/>
  <figcaption><strong>Figure 2:</strong> Navigating to the "Password Policy" section under the Default Domain Policy. This shows settings like password length, history, and complexity requirements.</figcaption>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/80e2df5f-0e3f-4d42-873d-c76bac7395a9" width="850"/>
  <figcaption><strong>Figure 3:</strong> Viewing the "Account Lockout Policy" settings, including lockout threshold, duration, and reset timing. These values help prevent brute-force login attempts.</figcaption>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/624a2b7c-2022-433c-addb-832e865c2777" width="850"/>
  <figcaption><strong>Figure 5:</strong> Viewing a locked-out user account in Active Directory. The "Unlock account" checkbox is shown under the user's properties.</figcaption>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/45f3b3f5-d8f9-4f39-9a48-e6eb330634f6" width="850"/>
  <figcaption><strong>Figure 6:</strong> Right-clicking a locked user to access the "Reset Password" option. This step is often performed when assisting users who’ve exceeded login attempts.</figcaption>
</p>




---


