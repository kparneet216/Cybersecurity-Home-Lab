# Nmap Service Enumeration

## Objective

The objective of this exercise was to identify active hosts, open ports and running services on the Metasploitable2 virtual machine.

---

## Environment

Attacking Machine:
- Kali Linux

Target Machine:
- Metasploitable2

Network:
- VMware Workstation NAT

---

## Tool Used

Nmap

---

## Command

```bash
nmap -sV <Target-IP>
```

---

## Purpose

The `-sV` option performs service version detection, allowing identification of applications running on open ports.

---

## Findings

The scan identified multiple open ports and network services including FTP, SSH, HTTP and SMB.

---

## Learning Outcome

This exercise demonstrated how attackers and security professionals enumerate network services before conducting further security assessments.

It also reinforced the importance of identifying unnecessary services that could increase an organization's attack surface.
