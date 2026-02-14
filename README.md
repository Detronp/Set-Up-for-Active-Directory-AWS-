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

---

### Step 3: Select Installation Type `[0:23]`

- Click **Next** to proceed past the introduction.
- Select **Role-based or feature-based installation**.
- Click **Next** to continue.

---

### Step 4: Select Active Directory Domain Services `[0:30]`

- From the roles list, select **Active Directory Domain Services**.
- When prompted, click **Add Features**.
- Confirm the selection.

---

### Step 5: Continue Installation Process `[0:41]`

- Click **Next** through the remaining configuration screens.
- Review selected features and roles.

---

### Step 6: Start Installation `[1:00]`

- Click **Install** to begin the Active Directory installation.
- Allow the process to complete without interruption.

---

## Cautionary Notes

- Do not close Server Manager or interrupt the installation once it has started.
- Ensure system resources remain stable during installation.

---

## Tips for Efficiency

- Verify prerequisites before starting to avoid installation errors.
- Monitor progress to quickly respond to any prompts.
