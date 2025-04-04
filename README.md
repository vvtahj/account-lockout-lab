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

---


