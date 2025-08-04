# Task 1: Scan Your Local Network for Open Ports
# Objective: Discover open ports on devices within my local network

# Tools Used: Nmap

# Steps to perform
1. Find local IP range using the command _"ip a"_
2. Perform a TCP SYN scan using the command _"nmap -sS 192.168.194.130/24"_
3. Scan host for Open Ports using command _"nmap -sS 192.168.194.130"_
4. Save scan results in text format using the command _"nmap -sS 192.168.194.130/24 -oN scan_results.txt"_
