# Wazuh SIEM Home Lab – Detection of Suspicious Activities
This project documents the setup and demonstration of a Wazuh SIEM system in a home lab environment. The primary focus is on configuring the SIEM to detect various suspicious activities, including brute-force attacks and the execution of malicious scripts

# Project Overview
The main objective of this home lab is to establish a practical and functional Wazuh SIEM environment. This setup serves as a platform for learning and experimenting with threat detection, log analysis, alert mechanisms, and incident response procedures in a controlled setting.

## 🔍 Project Goals

- Set up a working Wazuh SIEM system
- Monitor Windows & Linux endpoints
- Create and test custom detection rules
- Simulate real-world attacks
- Practice alert analysis and incident handling

![architecture](images/lab_diagram.png) 

## 🧪 Tools and Technologies

| Component        | Role                        |
|------------------|-----------------------------|
| Wazuh Server     | Log aggregation + analysis  |
| Windows 11       | Endpoint with agent + Sysmon |
| Ubuntu 22.04     | SSH target with agent       |
| Kali Linux       | Attacker                    |
| Hydra            | Brute-force tool            |

## 🧩 Key Steps

### 1. Wazuh Server Setup  
- Ubuntu 22.04, installed via official script  (https://documentation.wazuh.com/current/quickstart.html#quickstart)
- Enabled web dashboard + Wazuh manager  
  📷 ![server](images/server_setup.png)

---

