# Linux & Cloud Service Operations Lab

## Overview

This project simulates real-world workflows performed by Service Operations Analysts, Linux Administrators, and Cloud Support Engineers.

The lab is designed to replicate how engineers troubleshoot systems, analyze logs, manage services, and resolve network issues in production environments.

Each module focuses on hands-on command-line operations with real troubleshooting scenarios, mirroring responsibilities found in enterprise IT and cloud-based infrastructures.

---

## Objective

Build practical, job-ready Linux troubleshooting skills used in:

- Service Operations (SOC / NOC environments)
- Cloud Support Engineering (AWS / Azure)
- System Administration
- Incident Response & Production Support

This lab emphasizes **operational thinking**, not just commands — focusing on how engineers diagnose and resolve real issues.

---

## Lab Environment

- Ubuntu Server (VirtualBox)
- Terminal-based Linux administration
- GitHub for documentation and version control

---

## Core Skills Demonstrated

- Linux system navigation and file management  
- System performance monitoring and analysis  
- Service management using `systemctl`  
- Log analysis using `journalctl` and system logs  
- Network troubleshooting and diagnostics  
- Incident-style problem investigation  
- Command-line efficiency and troubleshooting workflows  

---

## Lab Structure

Each lab represents a core responsibility in a real operations role:

| Lab | Topic |
|-----|------|
| 01 | System Navigation |
| 02 | System Monitoring |
| 03 | Service Management |
| 04 | Log Analysis |
| 05 | Network Troubleshooting |

Each lab includes:

- Commands used
- Technical explanations
- Real-world use cases
- Screenshots of output
- Operational context

---

## Key Operational Workflows Practiced

- Diagnosing system issues using CLI tools  
- Investigating logs for security and system events  
- Restarting and validating services  
- Identifying CPU, memory, and process issues  
- Troubleshooting network connectivity and DNS failures  
- Verifying system configurations and dependencies  

---

## Real-World Relevance

This project mirrors tasks performed in:

- Incident response calls (high CPU, service failures)
- Linux server troubleshooting (SSH, services, logs)
- Cloud VM diagnostics (network + service validation)
- SOC investigations (authentication logs, failed logins)

The goal is to simulate **production-level thinking**, not just basic command usage.

---

## Example Scenarios Covered

- Service failure impacting system access  
- High CPU usage affecting application performance  
- Failed SSH login attempts indicating potential security concerns  
- DNS misconfiguration preventing external connectivity  
- Network routing issues blocking communication  

---

## Goal

Develop a strong foundation in Linux operations and troubleshooting to prepare for roles such as:

- Service Operations Analyst (Linux & Cloud)
- Cloud Support Engineer
- Systems Engineer
- Site Reliability Engineer (SRE)

---

## Future Enhancements (Next Phase)

- AWS EC2-based lab environments  
- CloudWatch monitoring integration  
- Infrastructure as Code (Terraform)  
- Simulated production incidents (CPU spikes, service outages)  
- Automated remediation scripts (Bash / Python)  

---

---

## Incident Simulation (Mini Project)

This lab also includes a simulated production-style incident involving high CPU usage impacting system performance.

### Scenario

Users experienced system slowness due to excessive CPU consumption caused by a runaway process.

### Investigation Steps

- Identified CPU spike using `top`
- Analyzed processes using `ps aux --sort=-%cpu`
- Checked service health using `systemctl status`
- Reviewed logs using `journalctl`

### Resolution

- Terminated the offending process using `kill -9 <PID>`
- Restarted affected services
- Validated system recovery

### Outcome

- System performance restored
- Services stabilized
- Root cause identified and documented

This simulation reflects real-world incident response workflows used in service operations and cloud environments.

## Author

Miguel Lopez  
Cloud & Systems Engineering Path  
