# Wireshark Packet Analysis

## Objective

Capture and analyse network traffic between Kali Linux and Metasploitable2.

---

## Environment

**Source:** Kali Linux

**Target:** Metasploitable2

**Network:** VMware NAT

---

## Tool

Wireshark

---

## Procedure

1. Started packet capture on the active network interface.
2. Generated traffic using the ping command.
3. Applied ICMP and DhCP filters.
4. Analysed captured packets.

---

## Observations

The capture successfully displayed communication between Kali Linux and Metasploitable2.

Observed information included:

- Source IP
- Destination IP
- MAC addresses
- ICMP Echo Requests
- ICMP Echo Replies
- TCP packets

---

## Learning Outcome

This exercise improved my understanding of packet analysis and network protocols. It demonstrated how Wireshark can be used to troubleshoot connectivity issues and analyse network traffic.
