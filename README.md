
# Implementing Zero Trust Network in an Enterprise Network

## Authors
- Ibrahim Khalid (Roll: 24114)  
- Md. Imran Hossen (Roll: 24115)  
- Md. Main Uddin (Roll: 24103)  

## Abstract
This project explores the design and implementation of a Zero Trust Network (ZTN) in an enterprise environment. Unlike traditional perimeter-based models, Zero Trust assumes no implicit trust and enforces strict identity verification and access control. The project integrates technologies like Active Directory, Microsoft Entra, Wazuh, Suricata, Cilium, and pfSense to build a secure, scalable, and resilient network. A prototype was deployed and evaluated, demonstrating improved security posture and reduced attack surface.

## Objectives
- Design and implement a Zero Trust Network using open-source tools.
- Strengthen enterprise security through identity management, network segmentation, and real-time monitoring.
- Demonstrate practical deployment and evaluation of Zero Trust principles.

## Tools & Technologies
- **Active Directory & Microsoft Entra** – Identity and access management
- **Suricata** – Intrusion detection and prevention
- **Wazuh** – SIEM and log analysis
- **Cilium** – Network micro-segmentation
- **pfSense** – Firewall and traffic control

## Implementation Overview
- Setup of Active Directory and Microsoft Entra for centralized identity management.
- Deployment of Cilium for network segmentation and access control.
- Integration of Suricata and Wazuh for real-time monitoring and threat detection.
- Configuration of pfSense for firewall enforcement and VPN access.

## Key Components of Zero Trust
- **Identities** – Users, services, and credentials with strong authentication.
- **Endpoints** – Secure all devices including BYOD and IoT.
- **Applications** – Controlled access and behavior monitoring.
- **Networks** – Segmentation and real-time traffic analysis.
- **Infrastructure** – Secure configurations and updates.
- **Data** – Classification, access control, and monitoring.

## Results
- **Authentication & Access Control** – Seamless integration of AD and Entra with MFA.
- **Network Segmentation** – Effective isolation of critical resources using Cilium.
- **Monitoring & Detection** – Real-time alerts from Suricata and Wazuh.
- **Firewall Enforcement** – Robust traffic control with pfSense.
- **Overall Impact** – Enhanced security posture and reduced risk of breaches.

## Future Work
- Extend Zero Trust to IoT and unmanaged devices.
- Explore integration with SASE for cloud-native security.
- Evaluate Zero Trust in containerized and multi-cloud environments.
- Incorporate AI/ML for adaptive threat detection and response.
