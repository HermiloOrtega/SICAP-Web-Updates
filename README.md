# 📦 SICAP Updater

## 🧭 Overview
**SICAP Updater** is a Windows application developed in C# to automatically synchronize operational data from the [**SICAP**](https://github.com/HermiloOrtega/SICAP) to [**SICAP Web**](https://github.com/HermiloOrtega/SICAP-Web) and [**SICAP Indicadores**](https://github.com/HermiloOrtega/SICAP-Indicators).

Its mission is to ensure KPIs, project tracking, and contract progress reporting are always up-to-date for directors, managers, administrative and technical staff, without manual intervention.

### Updates screen
![Screenshot](./assets/1.png)

### Error log
![Screenshot](./assets/2.png)

---

## 💡 Idea & Concept
- Automate the data refresh between operational (WinApp) and reporting (Web/Indicators) systems.
- Replace manual refresh tasks with a reliable and secure background service.
- Provide instant or scheduled updates to guarantee daily operational accuracy.

---

## ✨ Features & Functionality
- **Automated Scheduled Updates**:
  - Background service automatically updating KPIs and summary tables daily.
  
- **Manual Update Trigger**:
  - Manual update button available for urgent refresh needs.

- **Error Handling & Logging**:
  - Error capture with full detail (function, module, user, timestamp, exception message).
  - Logs saved for later troubleshooting and analysis.

- **System Tray Application**:
  - Runs quietly in the background.
  - Notification alerts in case of success, errors, or interruptions.

- **Secure Environment Selection**:
  - DEV, QAS, or PRD database environment selectable from the login interface.

- **Single Instance Enforcement**:
  - Ensures only one active instance runs on the system at any time.

- **Startup Integration**:
  - Configured to auto-launch on system startup ensuring 24/7 availability.

---

## ⚙️ Tech Stack
| Category                | Tools & Frameworks |
|-------------------------|--------------------|
| **Frontend**            | ![WinForms](https://img.shields.io/badge/WinForms-512BD4?logo=.net&logoColor=white&style=for-the-badge) |
| **Backend**             | ![C#](https://img.shields.io/badge/C%23-239120?logo=c-sharp&logoColor=white&style=for-the-badge) |
| **Platform**            | ![Windows App](https://img.shields.io/badge/Windows%20App-0078D4?logo=windows&logoColor=white&style=for-the-badge) |
| **Framework**           | ![.NET Framework](https://img.shields.io/badge/.NET%20Framework-512BD4?logo=.net&logoColor=white&style=for-the-badge) |
| **IDE**                 | ![Visual Studio](https://img.shields.io/badge/Visual%20Studio-5C2D91?logo=visualstudio&logoColor=white&style=for-the-badge) |
| **Database**            | ![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?logo=microsoft-sql-server&logoColor=white&style=for-the-badge) |
| **Analytics & Reporting** | ![Crystal Reports](https://img.shields.io/badge/Crystal%20Reports-000000?style=for-the-badge) |
| **Cloud & Hosting** | ![Windows Server](https://img.shields.io/badge/Windows%20Server-0078D4?logo=windows&logoColor=white&style=for-the-badge) ![IIS](https://img.shields.io/badge/IIS-0078D7?logo=microsoft&logoColor=white&style=for-the-badge) |
| **Security & Identity** | ![Custom Auth](https://img.shields.io/badge/Custom%20Auth-000000?style=for-the-badge&logo=key&logoColor=white) |
| **Other**               | ![SAP](https://img.shields.io/badge/SAP-000000?logo=sap&logoColor=white&style=for-the-badge) ![Windows Scheduled Tasks](https://img.shields.io/badge/Windows%20Scheduled%20Tasks-0078D4?logo=windows&logoColor=white&style=for-the-badge) |

---

## 🏗 Architecture & Design
- Scheduled data fetch and synchronization with minimal system footprint.
- Layered approach separating UI, business logic, and database access.
- Optimized stored procedures for quick synchronization cycles.
- Encrypted connection strings and secure database access.

---

## 🚀 Deployment & Hosting
- Installed on key internal servers with administrative permissions.
- Automated execution through Windows Task Scheduler during low traffic hours.

---

## 🧑‍💻 My Role & Contributions
- Full system design and development.
- Database optimization for rapid summary table updates.
- UI/UX simplification for manual triggers.
- Security enhancement for safe synchronization operations.

---

## 🧗 Challenges & Learnings
- Building a truly resilient and silent background service.
- Managing synchronization across development, QA, and production environments without collision.
- Ensuring error handling and recovery processes minimized operational risks.

---

## 📈 Future Enhancements
- Convert into a Windows Service instead of a user-launched app.
- Add monitoring dashboards for real-time update tracking.
- Automatic recovery and retry system for failed updates.

---

## 🤝 Project Type
Internal mission-critical tool for the **AHMSA** organization.

---

## 🪪 License
⚠️ Internal Use Only — Copyright reserved to AHMSA.
