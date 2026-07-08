# Advanced Nmap Scanning

## Objective

Perform advanced network reconnaissance against the Metasploitable2 virtual machine.

---

## Host Discovery

Command:

nmap -sn 192.168.x.0/24

Purpose:

Identify active hosts on the local network.

---

## TCP SYN Scan

Command:

nmap -sS <Target-IP>

Purpose:

Identify open TCP ports using a SYN scan.

---

## Service Detection

Command:

nmap -sV <Target-IP>

Purpose:

Determine services and application versions running on the target.

---

## Operating System Detection

Command:

nmap -O <Target-IP>

Purpose:

Attempt to identify the target operating system.

---

## Aggressive Scan

Command:

nmap -A <Target-IP>

Purpose:

Perform OS detection, version detection, script scanning and traceroute.

---

## Outcome

Successfully collected information about the target system for future security assessment.
