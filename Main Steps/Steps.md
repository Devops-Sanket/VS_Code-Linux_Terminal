## STEP 1: Install WSL (PowerShell)

1.  Open **PowerShell as Administrator**
    
2.  Run:
    

`wsl --install`

> This installs:

*   WSL 2
    
*   Ubuntu (latest)
    
*   Required Windows features
    

3.  **Restart your PC** when asked
    

* * *

## STEP 2: Check WSL Status (After Restart)

Open **PowerShell** again:

`wsl --list --verbose`

Expected output:

| NAME   | STATE   | VERSION |
|--------|---------|---------|
| Ubuntu | Running | 2       |

If Ubuntu is missing:

`wsl --install -d Ubuntu`

* * *

## STEP 3: Open Ubuntu & Create Linux User

1.  Open **Ubuntu** from Start Menu
    
2.  Wait for setup to complete
    
3.  Create:
    
    *   Linux username
        
    *   Linux password
        

You are now inside **Linux terminal** ✅

* * *

## STEP 4: Install VS Code (Windows)

Download and install VS Code:  
👉 [https://code.visualstudio.com/](https://code.visualstudio.com/)

During install, make sure these are checked:

*   ✅ Add to PATH
    
*   ✅ Register Code as editor
    
*   ✅ Add “Open with Code” (optional)
    

* * *

## STEP 5: Install WSL Extension in VS Code

1.  Open **VS Code**
    
2.  Press `Ctrl + Shift + X`
    
3.  Search:
    
    `WSL`
    
4.  Install **WSL (by Microsoft)**
    

* * *

## STEP 6: Open VS Code in Linux (WSL Mode)

### Method A (Recommended)

From **Ubuntu terminal**, run:

`code .`

### Method B (From VS Code UI)

1.  Press `Ctrl + Shift + P`
    
2.  Select:
    

`WSL: New WSL Window`

* * *

## STEP 7: Confirm VS Code Is Connected to Linux

Look at **bottom-left corner** of VS Code:

`WSL: Ubuntu-22.04`

✅ This confirms VS Code is running inside Linux.

* * *

## STEP 8: Open a Linux Folder (IMPORTANT)

1.  Click **File → Open Folder**
    
2.  Go to:
    

`/home/<your-linux-username>/`

Example:

`/home/sanket/`

3.  Open or create a project folder
    

⚠️ **Do NOT open**:

`C:\Users\...`

* * *

## STEP 9: Open Linux Terminal in VS Code

 You should see:

**`username@DESKTOP-XXXX:~$`** <br>
 **Ex. (Sanket@Linux:~$)**

* * *

## STEP 10: Set Linux Bash as Default Terminal

1.  `Ctrl + Shift + P`
    
2.  Select:
    

   `Terminal: Select Default Profile`

3.  Choose:
    

   `bash (WSL)`

Close terminal → open again.

* * *

## STEP 11: Verify Linux Environment

Run:

`uname -a`

Expected:

`Linux ...`

`pwd`

Expected:

`/home/username`

---
🎉 **VS Code terminal is now 100% Linux**
---





