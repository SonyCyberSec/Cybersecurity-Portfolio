# Manipulating and Viewing Virtual Memory Configuration

This lab guides you through adjusting and verifying virtual memory (paging file) settings in Windows. By the end of the lab, you will understand how to configure paging file sizes and confirm the changes within the system settings.

## Objective
Configure and verify virtual memory settings to understand how paging file size affects system performance.

## Requirements
- Windows 10, Windows 11, or Windows Server 2022 virtual machine
- Administrator access

## Steps

### Step 1: Configure Virtual Memory
1. Start the Windows virtual machine.
2. Press **Ctrl + Alt + Del** (or use VirtualBox → Input → Insert Ctrl+Alt+Del).
3. Log in using the password: `Password.1!!`
4. Open the Start Menu and search for **Settings**.
5. Search for **View advanced system settings** and open it.
6. Go to **Advanced** → **Performance** → **Settings**.
7. In the Performance Options window, go to **Advanced** → **Virtual memory (Change…)**.
8. Uncheck **Automatically manage paging file size for all drives**.
9. Select **Custom size** and enter:
   - Initial size: **500 MB**
   - Maximum size: **1500 MB**
10. Click **Set**, then **OK**.
11. Restart the system when prompted.

### Step 2: Verify the Configuration
1. Navigate again to:
   **Advanced System Settings → Performance → Settings → Advanced → Virtual Memory**
2. Confirm the values now reflect the new paging file size (500–1500 MB).

## Outcome
You successfully:
- Adjusted the paging file size
- Restarted the system to apply the change
- Verified the updated virtual memory configuration

