# Active Directory Home Lab

This project demonstrates a simple **Active Directory** lab using Windows Server 2022 and a Windows 10 client.  
It covers installing AD DS, creating a domain, adding Organizational Units (OUs) and users, and joining a client machine to the domain.

---

## Steps Performed
1. Installed **Windows Server 2022** and configured a static IP.
2. Installed **Active Directory Domain Services (AD DS)** role.
3. Promoted the server to a Domain Controller for the domain `lab.local`.
4. Created an **Organizational Unit (OU)** and a test user account.
5. Joined a Windows 10 client to the `lab.local` domain.
6. Verified login and connectivity with the domain user.

---

## Screenshots

- **AD DS Installed in Server Manager**  
  ![Server Manager](screenshots/01_servermanager.png)

- **Active Directory OU and User**  
  ![ADUC User](screenshots/02_aduc_user.png)

- **Ping test between Client and Domain (lab.local)**  
  ![Ping Test](screenshots/03_client & server_ping.png)

- **Verification with whoami on Client**  
  ![Whoami](screenshots/04_whoami.png)

---

## Tools Used
- Windows Server 2022 (Domain Controller)
- Windows 10 (Client)
- VMware Workstation / VirtualBox
- Active Directory Domain Services (AD DS)

---

## Purpose
This lab was created to practice **real-world IT support and networking scenarios**, including domain setup, user management, and troubleshooting.  
It serves as a **portfolio project** to demonstrate practical IT skills.
