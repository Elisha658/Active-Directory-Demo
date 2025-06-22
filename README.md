# Active Directory User Management Demo  
**Tools**: Windows Server, Active Directory Users & Computers  

---

## Step 1: Access AD Users & Computers  
![AD Users Interface](domain%20User%201.png)  
- Navigate to `Server Manager > Tools > Active Directory Users and Computers`.  
- Expand your domain (`El.local`) and select the `Users` OU.  

---

## Step 2: Create a New User  
![New User Form](domain%20user%202.png)  
- Right-click in the `Users` container → `New` → `User`.  
- Fill in:  
  - **First/Last name**: Bisha Tachie  
  - **Logon name**: `El.Tachie@El.local`  

---

## Step 3: Configure Password Policies  
![Password Settings](domain%20user%203.png)  
- Set password and enforce:  
  - ☑ *User must change password at next logon*  
  - ☐ Disable other options for security.  

---

## Step 4: Verify User Creation  
![User List](domain%20user%204.png)  
- New user "Elisha Tachie" appears in AD.  
- Confirms successful object creation.  
