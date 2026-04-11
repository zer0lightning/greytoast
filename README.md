# GreyToast

GreyToast is a browser-based toolkit for generating Windows 10/11 Toast Notification PowerShell script.

## ✨ Features

### 🧩 Core Functionality
- Visual toast notification builder
- Windows 11-style preview
- PowerShell script generation
- One-liner (Base64 encoded) execution support
- Fully client-side (no dependencies)

### 🎛️ Notification Customization
- AUMID (App User Model ID) support
- Scenario types:
  - Default
  - Urgent
  - Reminder
  - Alarm
  - Incoming Call UI
- Title, body, attribution
- Custom app logo path

### 🔘 Actions & Interaction
- Up to 2 action buttons
- Supported action types:
  - URL
  - Script / executable
  - Dismiss
- Optional user input:
  - Text input
  - Dropdown selection

### 🧪 Advanced Mode
- Full XML editor
  - Apply changes
  - Format XML
  - Validate structure
- Live sync between UI and XML

### 🖥️ Interface
- Windows 11-style toast rendering
- Dark mode UI
- Resizable panels (desktop)
- Mobile responsive layout


## 🚀 Getting Started

### Run Locally

1. Clone the repository  
   git clone https://github.com/zer0lightning/greytoast.git  

2. Open the app  
   cd greytoast  
   open index.html  

Or simply double-click `index.html`.

No installation or build step required.


## 🛠️ How It Works

GreyToast generates Windows toast notifications by:

1. Constructing a Toast XML payload  
2. Embedding it into a PowerShell script  
3. Executing via Windows APIs:

   - Windows.UI.Notifications  
   - ToastNotificationManager  


## 📂 Project Structure

```
greytoast/
├── index.html   # Entire application (UI + logic)
└── README.md
```


## 🧪 Use Cases

- IT automation & internal tooling  
- Notification UX prototyping  
- Security awareness demonstrations  
- Red team / adversary simulation research  
- Testing Windows notification behavior  


## ⚠️ Disclaimer

This tool is intended for:

- Educational use  
- Authorized security testing  

Do **not** use this tool for unauthorized phishing, deception, or malicious activity.

You are responsible for how you use this software.


## 🙏 Credits & References

GreyToast builds on research and tooling from the security and Windows ecosystem.

### 🔬 Research & Tools

- https://github.com/ivancabrera02/ToastNotifications  
  Core PowerShell toast implementation, AUMID references, and scenario groundwork  

- https://github.com/fox-it/Invoke-CredentialPhisher  
  Techniques and research into credential phishing via Windows toast notifications  

- https://ipurple.team/2026/03/25/toast-notifications/  
  Red team tradecraft and practical use of toast notifications  


### 📘 Documentation

- https://learn.microsoft.com/en-us/windows/apps/design/shell/tiles-and-notifications/toast-notifications-overview  
  Official Microsoft toast notification documentation  

- https://attack.mitre.org/techniques/T1204/001/  
  MITRE ATT&CK: User Execution (malicious link interaction)  


### 🧠 Technical Notes

- Uses:
  - Windows.UI.Notifications  
  - Windows.Data.Xml.Dom  

- UI scenarios inspired by real-world applications:
  - Microsoft Teams  
  - Windows Defender  
  - Google Chrome  


## 👤 Author

zer0Lightning  - https://github.com/zer0lightning  


## 🤝 Contributing

Contributions are welcome.

- Open issues for bugs or ideas  
- Submit pull requests for improvements  


## ⭐ Support

If you find this tool useful, consider starring the repository.
