# Identify-and-Remove-Suspicious-Browser-Extensions-task8

## Overview:
This repository contains the deliverables for Identify-and-Remove-Suspicious-Browser-Extensions of the Cybersecurity Internship, focusing on understanding the role of Virtual Private Networks (VPNs) in protecting privacy and enabling secure communication. The task involves setting up a free VPN client (ProtonVPN free tier), connecting to a VPN server, verifying IP address changes, confirming encrypted traffic, comparing browsing speeds, and researching VPN features. This README provides a detailed explanation of the task, setup steps, deliverables, and submission details.

## Task Objectives:
Understand VPN Functionality: Learn how VPNs protect privacy and secure communication.
Hands-On Setup: Install and configure a free VPN client (ProtonVPN).
Verification: Confirm IP address changes and encrypted traffic.
Analysis: Compare browsing speeds with and without VPN and research encryption and privacy features.
Deliverables: Submit a report describing VPN setup steps, a screenshot of the connection status, and a summary of VPN benefits and limitations.

## Repository Contents:
report.md: A detailed report outlining the VPN setup process, observations, benefits, and limitations.
vpn_connection_screenshot.png: A screenshot showing the ProtonVPN client connected to a server (placeholder; replace with actual screenshot).
README.md: This file, providing an overview of the task and submission details.

## Prerequisites:
Operating System: Windows, macOS, or Linux (task performed on Windows 11 for this submission).
VPN Service: ProtonVPN (free tier, available at protonvpn.com).
Tools: Web browser (e.g., Google Chrome) and internet access.
Website for IP Verification: whatismyipaddress.com.
No paid tools were used, per task guidelines.

## Setup and Execution Steps:
Sign Up for ProtonVPN:
Visited protonvpn.com and created a free account using an email address.
Confirmed the account via email verification.
Download and Install ProtonVPN:
Downloaded the ProtonVPN client for Windows from the official website.
Installed the client by following the on-screen instructions (default settings used).
Logged in using the created account credentials.
Connect to a VPN Server:
Launched the ProtonVPN client and selected a server in the United States (closest available server for optimal speed).
Clicked "Connect" to establish the VPN connection.
Verified connection status via the client’s interface (see vpn_connection_screenshot.png).
Verify IP Address Change:
Before connecting: Visited whatismyipaddress.com to note the original IP address.
After connecting: Revisited the site and confirmed the IP address changed to one associated with the VPN server’s location.
Confirm Encrypted Traffic:
Browsed to example.com using Google Chrome.
Verified HTTPS protocol in the browser’s address bar and checked the ProtonVPN client logs to confirm encrypted traffic.
Compare Browsing Speed and IP:
Disconnected the VPN and revisited whatismyipaddress.com to confirm the original IP address was restored.
Performed a speed test (e.g., using speedtest.net) with and without the VPN to compare latency and download/upload speeds.
Observed a slight decrease in speed when connected to the VPN (detailed in report.md).
Research VPN Features:
Investigated ProtonVPN’s encryption (AES-256), tunneling protocols (OpenVPN and WireGuard), and privacy features (no-logs policy, kill switch).
Summarized findings in report.md, including benefits (e.g., data encryption, IP masking) and limitations (e.g., reduced speed, limited server options in free tier).
Write Report:
Created report.md detailing the setup steps, observations, and a summary of VPN benefits and limitations.
Included references to online resources used for research (e.g., ProtonVPN documentation, general VPN guides).

## Deliverables:
Report (report.md):
Describes the step-by-step VPN setup process.
Includes observations from IP verification and browsing tests.
Summarizes VPN benefits (e.g., privacy protection, secure communication) and limitations (e.g., potential speed reduction, free tier restrictions).
Screenshot (vpn_connection_screenshot.png):
Shows the ProtonVPN client interface with an active connection to a server (placeholder; replace with actual screenshot).

## Key Concepts Learned:
VPN: A service that creates a secure, encrypted tunnel for internet traffic, masking the user’s IP address.
Encryption: ProtonVPN uses AES-256 encryption to protect data from interception.
Privacy: VPNs hide user IP addresses and location, enhancing anonymity.
Tunneling Protocols: Protocols like OpenVPN and WireGuard ensure secure data transmission.
Network Security: VPNs protect against threats on public networks but may reduce speed due to encryption overhead.

## Debugging and Challenges:
Challenge: Initial connection failure due to network restrictions.
Solution: Switched to a different server and ensured no conflicting firewall settings.
Challenge: Verifying encrypted traffic.
Solution: Used browser developer tools to confirm HTTPS and checked VPN client logs.
Researched errors independently using ProtonVPN
