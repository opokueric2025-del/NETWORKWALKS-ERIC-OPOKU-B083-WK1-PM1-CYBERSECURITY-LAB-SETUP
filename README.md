# NETWORKWALKS – CYBERSECURITY LAB SETUP

## Week 1 – Project Module 1

### 1. Project Overview

This project focuses on setting up a cybersecurity testing laboratory using Oracle VirtualBox and Kali Linux.

The purpose is to create a virtual environment for learning and practising cybersecurity concepts safely.

### 2. Tools Used

* Oracle VirtualBox
* Kali Linux
* Windows 11 Host Machine

### 3. Lab Setup

The following tasks were completed:

1. Installed and opened Oracle VirtualBox.
2. Downloaded and imported the Kali Linux virtual machine.
3. Started the Kali Linux virtual machine.
4. Configured and activated the wired network connection.
5. Checked the network interface and IP configuration.
6. Tested connectivity to the default gateway.
7. Tested internet connectivity using Google.

### 4. Network Connectivity Tests

The following tests were performed:

* Checked network interfaces using `ip -br addr`.
* Checked routing information using `ip route`.
* Tested gateway connectivity using `ping`.
* Tested DNS resolution using `ping google.com`.
* Tested HTTPS connectivity using `curl -I https://google.com`.

**Result:** The Kali Linux virtual machine successfully connected to the network and accessed Google through HTTPS.

### 5. Challenges Encountered

During the setup, the wired network connection initially showed as disconnected.

There were also some difficulties configuring the network connection through the terminal.

### 6. Solutions

The network connection was deactivated and activated again using NetworkManager commands.

After that, the network interface became active and received an IP address.

Connectivity tests were performed to confirm that the network was working.

### 7. Conclusion

The cybersecurity testing environment was successfully set up using Oracle VirtualBox and Kali Linux.

This project provided practical experience in virtualisation, Linux networking, IP configuration and basic network troubleshooting.

### 8. Screenshots

Screenshots of the following activities will be included as project evidence:

* Kali Linux running in VirtualBox.
* Network interface and IP address.
* Routing table.
* Successful gateway connectivity test.
* Successful internet connectivity test.

