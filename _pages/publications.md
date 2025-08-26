---
layout: archive
title: "Projects"
permalink: /publications/
author_profile: true
---

## **Autopilot for Migration Project**  
 The Autopilot for Migration project aimed to streamline and automate the deployment, configuration, and management of new devices across the organization using Microsoft’s Autopilot and Endpoint Manager. This project was critical in supporting the company’s migration from traditional, manual device imaging methods to a modern, cloud-based solution. By leveraging Autopilot, we reduced deployment times, minimized IT overhead, and ensured a consistent and secure configuration for all new devices.

 ### Project Objectives:

 - Automate the deployment process of Windows 10/11 devices using Microsoft Autopilot.
 - Standardize device configuration profiles to maintain compliance and security standards.
 - Simplify the onboarding process for end-users, providing a zero-touch experience.
 - Integrate Autopilot with Azure Active Directory and Intune for seamless device management.
 - Ensure all devices receive pre-configured security baselines and required applications.

### Key Contributions:
- Developed and deployed Autopilot profiles and configuration policies in Endpoint Manager.
- Collaborated with the IT team to create customized deployment scripts for device enrollment and application installation.
- Integrated Azure Active Directory group policies to automate the assignment of configurations and application installations based on the user's role and department.
- Conducted pilot testing to identify and resolve any compatibility or deployment issues before full-scale rollout.
- Provided documentation and training to the IT support team and end-users to ensure smooth adoption and ongoing support.

### Achievements:

- Reduced device deployment time by 70%, lowering the average setup time from several hours to under 30 minutes per device.
- Enabled a zero-touch deployment model, which significantly improved the onboarding experience for remote employees.
- Achieved a 95% satisfaction rate in post-deployment user surveys due to the increased efficiency and reduced downtime.
- Improved security posture by enforcing device compliance policies and automatic installation of security updates.

### Technologies Used:

- Microsoft Autopilot: Automated device provisioning and configuration.
- Microsoft Endpoint Manager (Intune): Centralized management of devices, applications, and policies.
- Azure Active Directory: Seamless authentication and access management.
- PowerShell Scripting: Customized scripts for automation and troubleshooting.

This project not only modernized the device deployment process but also laid a strong foundation for future scalability and integration of more advanced IT solutions across the organization.

## **Always On VPN Deployment with Device Tunnel and User Tunnel Integration**
The Always On VPN project focused on implementing a robust and secure remote connectivity solution that provided seamless, on-demand access for both corporate-managed devices and users. By leveraging Always On VPN with device tunnel and user tunnel configurations, we enabled secure, granular access to internal resources for remote workers while maintaining strict compliance and security standards. This solution was integrated with Azure and Intune to ensure centralized management and simplified deployment, reducing administrative overhead and enhancing user experience.

### Project Objectives:

- Implement an Always On VPN solution with device tunnel for background services and user tunnel for interactive user connections.

- Enhance security by configuring multi-factor authentication (MFA) and conditional access policies in Azure Active Directory.

- Seamlessly integrate the VPN solution with Microsoft Intune for policy management, compliance monitoring, and automatic deployment.

- Provide a reliable, always-on connection that supports automatic reconnection and persistent access to corporate resources without user intervention.

- Minimize user impact by providing a consistent and transparent VPN experience across different network conditions.

### Key Contributions:

- Designed and configured the Always On VPN infrastructure using Windows Server and Network Policy Server (NPS) to handle VPN authentication and authorization.

- Implemented device tunnel configuration for pre-logon connections, allowing system-level tasks, such as domain authentication and group policy application, to occur even before a user logs in.

- Configured the user tunnel to provide user-specific access to internal applications and resources based on the role and group membership.

- Integrated VPN profile deployment with Microsoft Intune, automating the provisioning of VPN settings, certificates, and compliance policies to devices.

- Utilized Azure Conditional Access policies to enforce secure access, ensuring that only compliant and authenticated devices could establish VPN connections.

### Achievements:

- Achieved a 50% reduction in VPN-related helpdesk tickets due to the improved reliability and automatic reconnection features of Always On VPN.
- Enhanced security posture by enforcing MFA and compliance checks before establishing a user tunnel connection.
- Provided remote workers with uninterrupted access to corporate resources, even during network transitions, resulting in increased productivity and reduced downtime.
- Enabled faster and easier deployment of VPN configurations through Intune, reducing the time needed to onboard new devices by over 60%.
- Successfully scaled the solution to support over 500 remote users with minimal impact on network performance or server resources.

### Technologies Used:

- Always On VPN (Device Tunnel & User Tunnel): Configured for secure, persistent connections at both system and user levels.

- Microsoft Intune: Deployed VPN profiles, managed compliance policies, and monitored device health.

- Azure Active Directory: Managed authentication and conditional access policies to enforce secure connections.

- Network Policy Server (NPS): Handled RADIUS authentication and authorization for VPN connections.

- Windows Server: Hosted the VPN infrastructure and handled IPsec configurations.

This deployment successfully replaced legacy VPN solutions, provided more granular control over resource access, and offered a superior remote work experience for end-users. The integration with Azure and Intune ensured the solution could be centrally managed and scaled easily to meet future needs.



---

## Master thesis

**Incorporating Replication Techniques for Resilient Service Execution in Edge-Cloud Environments**  
**Aicha Garci**  
*Universitaät Passau, 2020*  
<!-- [[Thesis](https://arxiv.org/abs/2203.08038)]   -->