📘 Nexo Browser – Exit Codes Documentation

🧾 Overview



This document defines all miscellaneous return codes used by Nexo Browser Installer and Application. These codes are used to indicate success states, user actions, system errors, and installation failures.



✅ Success Codes

Code	Name	Description

0	Installation successful	Installation completed successfully without errors.

👤 User Actions

Code	Name	Description

1602	Installation cancelled	The installation was cancelled by the user.

📦 Installation State Errors

Code	Name	Description

4253	Application already exists	The application is already installed on this device.

3432	Installation already in progress	Another installation is currently running. Finish it before starting a new one.

💾 System Resource Errors

Code	Name	Description

355	Disk space full	Not enough disk space available to complete installation.

3010	Reboot required	A system restart is required to complete installation or updates.

🌐 Network Errors

Code	Name	Description

34	Network failure	A network error occurred during download or installation.

🔐 Security / Policy Errors

Code	Name	Description

1345	Package rejected	Installation blocked due to system security policy or administrator restrictions.

🧠 Notes

Exit code 0 always indicates success

Any non-zero code indicates an error or special system state

Codes are subject to extension in future versions of Nexo Browser

🚀 Version

Nexo Browser Installer: v1.0

Document version: 1.0

