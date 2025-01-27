# Automated Cybersecurity Event Analysis

## Overview

The **Automated Cybersecurity Event Analysis** project is an innovative solution designed to enhance the security posture of university campus networks. By leveraging data analytics and cybersecurity principles, the project focuses on automating threat detection, improving incident response, and creating a secure, resilient network infrastructure.

This repository contains the implementation details, methodologies, and documentation for building a virtualized network environment with advanced security features. Key components include a next-generation firewall, SIEM systems, intrusion detection and prevention systems (IDS/IPS), and an integrated ticketing system for incident management.

## Features

- **Virtual Campus Network Topology**: Simulates a scalable and secure network infrastructure for university environments.
- **Custom IDS System**: Detects anomalies, logs events, and mitigates security threats in real time.
- **Integration with Open-Source Tools**:
  - **OPNsense Firewall**: Configured with Nginx WAF and advanced monitoring tools like Ntopng.
  - **Splunk & Wazuh**: Provide centralized log analysis, event correlation, and threat detection.
  - **Slack Integration**: Streamlines incident management with real-time notifications and ticketing.
- **Attack Simulations**: Tests system effectiveness against common attack vectors such as DDoS, SQLi, and XSS.
- **Economic Optimization**: Implements cost-effective open-source tools to reduce operational overhead and enhance accessibility.

## Technologies Used

- **Firewall**: OPNsense with ZenArmor and Nginx WAF
- **Virtualization**: VMware Workstation Pro
- **SIEM Solutions**: Splunk, Wazuh
- **Security Monitoring**: Ntopng for traffic analysis
- **Collaboration**: Slack for real-time alerts and ticketing integration
- **Development Tools**: Python, Bash

## Key Objectives

1. Construct a secure and scalable campus network topology.
2. Implement an IDS system tailored for academic environments.
3. Automate incident detection and resolution workflows.
4. Enhance learning through attack simulations and detailed log analysis.

## Architecture

The project adopts a hybrid network topology combining mesh and star configurations for optimal connectivity and security. Key components include:

- **DMZ (Demilitarized Zone)**: Segregated network for external-facing services.
- **Dedicated Servers**: Web and mail servers with robust configurations.
- **Firewall & Monitoring**: Centralized security enforcement with integrated logging and analytics.

## Future Work

- Upgrade to **WPA3** for wireless security.
- Introduce **Intrusion Prevention Systems (IPS)** for active threat mitigation.
- Incorporate **machine learning** to enhance anomaly detection.
- Develop a comprehensive **backup and disaster recovery strategy**.

## How to Use

1. Clone this repository to your local machine.
2. Follow the setup instructions for:
   - OPNsense Firewall
   - Splunk & Wazuh
   - Slack integration for ticketing
3. Deploy the virtual network using VMware Workstation Pro.
4. Simulate attacks and monitor system responses in real time.

## Contributors

- **Nuray Gurbanova**
- **Azarin Bayali**
- **Gabil Gurbanov**

### Advisors

- **Mr. Nariman Aliyev**
- **Natig Zeynalzade (Code Academy)**
- **Orkhan Mammadov (Lead Infrastructure Manager, ADA University)**

