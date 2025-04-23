# 📦 SICAP Updater

## 🧭 Overview
**SICAP Updater** is a Windows application developed using C# that connects to an existing SQL Server database (originally created for another project).
Its primary objective is to automatically run scheduled updates for the SICAP Web system, ensuring that the displayed data is always up to date.
A manual update button is also provided for on-demand updates.

## 💡 Idea & Concept
The goal of SICAP Updater is to automate the process of updating the SICAP Web system with critical data.
Data is retrieved from the SICAP Windows application, processed, and summarized into various modules for display on SICAP Web.

Key modules include:
- Projects Active
- Projects Close to Finish
- Estimations
- Estimations for Different Companies
- Additionals and Excedents
- Advances
- Estimation Days

Additional features:
- **Error Log:** To monitor and display issues during updates.
- **Secure Access with Encryption:** All credentials and communication are encrypted.
- **System Tray Integration:** Runs in the system tray for easy access and notifications.

## ✨ Features & Functionality
- **Automated Scheduled Updates:** Updates run at defined intervals.
- **Manual Update Button:** Instant update option.
- **Data Summarization:** Modules for project and estimation data.
- **Error Log:** Displays issues for troubleshooting.
- **Secure Access:** Encrypted credentials and data transmission.
- **System Tray Integration:** Seamless background operation and quick access.

## ⚙️ Tech Stack
- **Platform:** Windows Application
- **Programming Language:** C#
- **Database:** SQL Server
- **Tools:** Windows Task Scheduler, System Tray API

## 🏗 Architecture & Design
- Pulls and processes data from SICAP application.
- Summarizes data and pushes it to SICAP Web.
- Runs in the background with system tray integration.
- Uses encrypted channels and credentials.
- Designed for local deployment with robust logging.

## 🚀 Installation & Setup
- **Prerequisites:** Windows OS, .NET Framework, SQL Server
- **Deployment:** Installed on local machine, configured via Windows Task Scheduler
- **Access:** Operates from the system tray with secure, internal-only access

> **Note:** Setup is managed by internal IT team.

## 🧑‍💻 Usage
1. Automatic updates run on a schedule.
2. Manual updates can be triggered anytime.
3. View the error log for troubleshooting.
4. Access app via system tray icon next to the clock.

## 🔍 My Role & Contributions
- 💼 Developed the full application
- 🧱 Designed integration with SQL Server
- 🐞 Implemented error logging and scheduling
- 🤝 Secured the app with encryption and enhanced UX with system tray features

## 🧗 Challenges & Learnings
- Ensured accuracy and consistency in automated updates.
- Integrated with existing legacy SICAP systems.
- Enhanced usability with low-disruption design.
- Implemented secure data transmission practices.

## 📈 Future Enhancements
- More detailed logging and diagnostics.
- Flexible scheduling configuration.
- Advanced analytics and reporting modules.

## 🤝 Contributing
Internal tool — feedback and enhancements are handled internally. Contact the project lead for input.

## 🪪 License
⚠️ License Notice  
This repository was originally published under the MIT License.  
As of April 22, 2025, the license has been changed to **CC BY-NC-ND 4.0**.  
See the LICENSE file for details.

## 🔗 Additional Resources
- **Related Projects:** SICAP Web, SICAP Windows App
- **Microsoft Relevance:** Advanced C#, SQL Server, system tray app design.