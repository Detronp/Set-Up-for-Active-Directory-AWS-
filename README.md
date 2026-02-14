# Set-Up-for-Active-Directory-AWS-
# Active Directory Setup via Remote Desktop

---

## Objective

This document provides clear steps for installing **Active Directory Domain Services (AD DS)** on a server through a Remote Desktop connection.

---

## Prerequisites

- Successful Remote Desktop connection to the server  
- Administrative permissions on the system  
- Server Manager available and accessible  

---

## Procedure

### Step 1: Access Remote Desktop `[0:00]`

- Log into the server using Remote Desktop.
- Confirm you have the required administrative permissions.

---

### Step 2: Add Roles `[0:08]`

- In **Server Manager**, locate the option to add roles.
- Click **Add Roles** to begin the setup wizard.
<img width="967" height="418" alt="image" src="https://github.com/user-attachments/assets/a1823c19-807a-4cd2-ba61-d19f96dc278f" />

---

### Step 3: Select Installation Type `[0:23]`

- Click **Next** to proceed past the introduction.
- Select **Role-based or feature-based installation**.
- Click **Next** to continue.
<img width="1202" height="672" alt="image" src="https://github.com/user-attachments/assets/4438eeaf-1667-4942-b55e-96be921f8f37" />

---

### Step 4: Select Active Directory Domain Services `[0:30]`

- From the roles list, select **Active Directory Domain Services**.
- When prompted, click **Add Features**.
- Confirm the selection.
<img width="1262" height="661" alt="image" src="https://github.com/user-attachments/assets/82eeb26a-871f-4ab7-910f-4ff13d0e0f33" />
<img width="991" height="640" alt="image" src="https://github.com/user-attachments/assets/f9982b86-7d3f-4b6d-986e-85fe926c9963" />

---

### Step 5: Continue Installation Process `[0:41]`

- Click **Next** through the remaining configuration screens.
- Review selected features and roles.
<img width="1099" height="705" alt="image" src="https://github.com/user-attachments/assets/a24fd2c8-9faa-454f-a06c-3a256ffdf592" />

---

### Step 6: Start Installation `[1:00]`

- Click **Install** to begin the Active Directory installation.
- Allow the process to complete without interruption.
<img width="1020" height="706" alt="image" src="https://github.com/user-attachments/assets/f1b7fb47-a124-4b28-a157-709f82c75d58" />

---

## Cautionary Notes

- Do not close Server Manager or interrupt the installation once it has started.
- Ensure system resources remain stable during installation.

---

## Tips for Efficiency

- Verify prerequisites before starting to avoid installation errors.
- Monitor progress to quickly respond to any prompts.
