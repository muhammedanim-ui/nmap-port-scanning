# Nmap Port Scanning Lab

## Overview

This project demonstrates practical network reconnaissance and port scanning using Nmap in a controlled cybersecurity lab environment.

The purpose of the project was to understand how Nmap can be used to identify open ports, running services, service versions, and operating system information on a target machine.

All scanning activities were performed in an authorised virtual lab environment.

## Objectives

- Learn the fundamentals of network reconnaissance.
- Identify open ports on a target machine.
- Identify services running on open ports.
- Detect service and software versions.
- Perform operating system detection.
- Understand how Nmap can be used during security assessments.
- Analyse and document scan results.

## Lab Environment

| Component | Details |
|---|---|
| Attacker | Kali Linux |
| Target | Metasploitable / Lab VM |
| Tool | Nmap |
| Virtualisation | VirtualBox |
| Network | Isolated virtual network |

## Nmap Scans

### 1. Basic Port Scan

A basic scan was used to identify commonly accessible TCP ports and the services associated with them.

```bash
nmap <TARGET-IP>
