# 📦 SICAP Updater

## 🧭 Overview
**SICAP Updater** is a robust Windows desktop application developed in C# to automate and streamline the data refresh process for the SICAP Web system. 

It connects to an existing SQL Server database and periodically processes critical business data from the legacy SICAP Windows application into modern web-consumable summaries. A manual update option is also available, giving users full control when needed.

This application runs silently in the background via the system tray and was built with a strong focus on automation, performance, and data security.

## 💡 Idea & Concept
The application was created to eliminate the manual data refresh routine that supported SICAP Web's dashboards and KPIs. My goals were to:
- Automate periodic updates and reduce human error.
- Keep executive dashboards always up-to-date.
- Provide on-demand update control via a manual trigger.
- Ensure secure, traceable, and reliable operations.

Key data modules include:
- Active Projects
- Near-Completion Projects
- Estimations (by Company and Category)
- Additional Works / Overruns
- Advance Payments
- Estimation Days Tracker

## ✨ Features & Functionality
- ⏰ **Automated Scheduled Updates** via Windows Task Scheduler
- 🖱 **Manual Update Button** for real-time refresh
- 📊 **Data Summarization Engine** to optimize SICAP Web consumption
- 📋 **Error Logging Panel** for real-time diagnostics
- 🔐 **Secure Access** with encrypted credentials and communication
- 🪟 **System Tray Integration** for minimal disruption and quick access

## ⚙️ Tech Stack
- **Language**: C#
- **Platform**: Windows Forms (.Net Framework)
- **Database**: SQL Server
- **Utilities**: Windows Task Scheduler, System Tray API
- **Security**: Encrypted connection strings, secured DB access

## 🏗 Architecture & Design
- Pulls real-time operational data from legacy SICAP Windows app DB
- Processes and summarizes into optimized reporting tables
- Designed to run silently with system tray icon and background thread
- All sensitive operations (like DB updates) are secured and logged
- Error handling, fallback strategies, and clear logging ensure reliability

## 🚀 Installation & Setup
- **Requirements**: Windows OS, .NET Framework, SQL Server access
- **Deployment**: Local installation on designated server or admin workstation
- **Scheduling**: Managed through Windows Task Scheduler with custom intervals
- **Access**: Admin-only; runs silently from system tray for low disruption

> **Note**: Internal deployment and maintenance handled by IT/Dev team.

## 🧑‍💻 My Role & Contributions
- 💻 Sole developer of the SICAP Updater system
- 🧠 Architected update flow, scheduling logic, and DB integration
- 🔒 Designed and implemented secure credential handling
- 🔧 Developed error handling and user notification via tray icon
- 🧪 QA tested with actual SICAP Web loads and validated against source system

## 🧗 Challenges & Learnings
- Implemented real-world automation and data sync pipelines
- Navigated cross-system integration between WinForms and Web stacks
- Built an efficient data summarization layer from complex legacy systems
- Gained hands-on experience with secure Windows services and background task design
- Learned to manage long-running background processes with robust fault tolerance

## 📈 Future Enhancements
- Dynamic scheduling configuration UI for power users
- Webhook support for real-time status reporting
- Enhanced export/logging to SharePoint or centralized dashboard
- Historical update tracking and analytics

## 🤝 Contributing
This is an internal enterprise tool. Feedback and enhancements are handled by the in-house development and IT operations team.

## 🪪 License
⚠️ **License Update**  
Originally published under MIT. As of April 22, 2025, this project follows the **CC BY-NC-ND 4.0** license.  
See LICENSE file for usage limitations.

## 🔗 Additional Resources
- **Related Projects**: [SICAP Web](#), [SICAP Windows App](#)
- **Microsoft Relevance**: Demonstrates advanced C# desktop automation, SQL Server optimization, and secure integration patterns consistent with enterprise-scale tools.
