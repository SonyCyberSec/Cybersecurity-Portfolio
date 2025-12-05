# 📘 Manipulating and Viewing Virtual Memory Configuration

A hands-on lab demonstrating how to configure and verify virtual memory (paging file) settings in Windows. This README includes collapsible sections for cleanliness and GitHub-friendly formatting.

---

## 📑 Table of Contents
- [Overview](#overview)
- [Objective](#objective)
- [Tools Required](#tools-required)
- [Prerequisites](#prerequisites)
- [Lab Steps](#lab-steps)
  - [Step 1: Configure Virtual Memory](#step-1-configure-virtual-memory)
  - [Step 2: Verify Configuration](#step-2-verify-configuration)
- [Outcome](#outcome)
- [Additional Materials](#additional-materials)
- [Author](#author)

---

## 📄 Overview

This lab teaches you how to manually adjust the paging file size in Windows to optimize system performance and understand memory management at the OS level.

---

## 🎯 Objective

Configure, manage, and verify paging file (virtual memory) settings on a Windows system.

---

## 🧰 Tools Required

- Windows 10, Windows 11, or Windows Server 2022 VM  
- Administrator access

---

## 📚 Prerequisites

None — beginner-friendly.

---

# 🧪 Lab Steps

---

<details>
<summary><h2>Step 1: Configure Virtual Memory</h2></summary>

1. Start the Windows virtual machine.  
2. Use **Input → Keyboard → Insert Ctrl+Alt+Del** to unlock the VM.  
3. Log in with the password: `Password.1!!`  
4. Open the **Start Menu** and search for **Settings**.  
5. Search for **View advanced system settings** and open it.  
6. Under **System Properties → Advanced**, click **Settings** under *Performance*.  
7. In **Performance Options → Advanced**, click **Change…** under *Virtual memory*.  
8. Uncheck **Automatically manage paging file size for all drives**.  
9. Select **Custom size**, then enter:  
   - Initial size: **500 MB**  
   - Maximum size: **1500 MB**  
10. Click **Set** → **OK**.  
11. Restart the machine when prompted.  

</details>

---

<details>
<summary><h2>Step 2: Verify Configuration</h2></summary>

1. After restart, repeat navigation to:  
   **Advanced System Settings → Performance → Advanced → Virtual Memory**  
2. Confirm paging file values updated successfully from defaults (e.g., **1408 MB**) to the newly configured **500–1500 MB** range.  

</details>

---

## ✅ Outcome

By completing this lab, you have:

- Adjusted the system’s paging file manually  
- Observed how virtual memory affects performance  
- Verified system configuration changes through the GUI  

---

## 📦 Additional Materials

This repository includes supporting student/instructor files:

- **Lab Report Template (.docx)**  
- **Virtual Memory Lab Presentation (.pptx)**  
- **Student Handout (.pdf)**  

---

## 🏷 Author

This README supports the lab:  
**“Manipulating and Viewing Virtual Memory Configuration.”**


