# SOAR EDR Project: Automated Threat Detection and Response

## Overview

This project demonstrates the implementation of a Security Orchestration, Automation, and Response (SOAR) solution integrated with Endpoint Detection and Response (EDR) capabilities. By combining the power of SOAR and EDR technologies, we've created an automated system for detecting and responding to potential security threats with minimal human intervention.

## Key Components

- **EDR**: [LimaCharlie](https://limacharlie.io/)
- **SOAR**: [Tines](https://www.tines.com/)
- **Simulated Threat**: [Lazagne](https://github.com/AlessandroZ/LaZagne) (open-source password recovery tool)
- **Environment**: [Windows Server](https://www.microsoft.com/en-us/windows-server) virtual machine on VirtualBox

## Features

- Custom threat detection rules
- Automated alert generation and distribution
- Multi-channel notifications (Slack and email)
- User-in-the-loop decision making for critical actions
- Flexible response options (machine isolation or flagging for investigation)
- Detailed event logging for forensics

## Workflow

1. Threat detection on endpoints
2. Alert generation and processing
3. Information extraction and notification
4. User decision prompt
5. Automated response actions

## Benefits

- Rapid threat response
- Consistent handling of security incidents
- Scalable solution for multiple simultaneous threats
- Flexible and adaptable to evolving threat landscapes
- Improved visibility into security events

## Project Status

This repository contains an overview of our SOAR EDR project. We are currently working on detailed documentation that will guide you through the setup process step-by-step. Stay tuned for updates!

## Contributors

This project was developed collaboratively by [Alaa Eddine Ayedi](https://github.com/nattycoder) and [Ranim Hassine](https://github.com/ranimhassine).

## Detailed Project Documentation

For a comprehensive understanding of the project, including detailed setup instructions and in-depth explanations of each component, please refer to our detailed project documentation:

[Project_Documentation.pdf](./Cybersecurity_Soar_EDR_Project.pdf)

This PDF provides step-by-step guidance on setting up the environment, configuring LimaCharlie and Tines, and implementing the automated workflow.

## Coming Soon

- Detailed setup instructions for LimaCharlie
- Guide to creating Tines stories for this workflow
- Best practices for custom detection rule creation
- Troubleshooting tips and common issues

## Resources

- [LimaCharlie Documentation](https://docs.limacharlie.io/)
- [Tines Documentation](https://www.tines.com/docs)
- [Lazagne GitHub Repository](https://github.com/AlessandroZ/LaZagne)
- [Windows Server Documentation](https://docs.microsoft.com/en-us/windows-server/)

## Disclaimer

This project is for educational and demonstration purposes only. Always ensure you have proper authorization before deploying security tools in any environment.

---

For more detailed information about the project, please refer to the Project_Documentation.pdf file in this repository.
