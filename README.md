# Active Directory Homelab Project

This repository contains the configuration files and screenshots for my Active Directory homelab project. The project simulates a real-world IT infrastructure using VirtualBox on a NAT network and includes:

- **Virtual Machines Setup:**
  - **Windows Server:** Hosting Active Directory Domain Services.
  - **Windows 10 Client:** Joined to the domain.
  - **Ubuntu-based Splunk Server:** Configured for log ingestion and real-time monitoring.
  - **Kali Linux Machine:** Used for security testing and simulated attacks.

- **Security Monitoring:**
  - **Sysmon:** Installed on Windows machines for detailed logging.
  - **Splunk:** Configured with a custom `input.conf` file to capture events like failed logon attempts (Event Code 4625) and unauthorized user creation.

- **Attack Simulation:**
  - Conducted brute-force attack simulations to trigger key indicators of compromise.

## Contents

- **config/**: Contains configuration files.
  - `input.conf` - Splunk input configuration.
- **screenshots/**: Contains images of the project setup and outputs.
  - Replace the placeholder images with your actual screenshots.

Feel free to explore the repo to see how I set up and documented this project.
