# IP-Scanner

A simple subnet IP scanner built using a Bash ping loop to discover active hosts on a local network.

## What I Learned
- Bash `if-else` conditions and `for` loops
- Command substitution using `$(seq)`
- Output filtering and parsing with `grep`, `cut`, and `tr`
- Running background processes (`&`) and `wait` for faster execution

## Usage
1. Give execute permission:
   `chmod +x ip-scanner.sh`
2. Run the script with the first three octets of your IP:
   `./ip-scanner.sh 192.168.1`

## Limitation
This script only uses ICMP ping requests. If a target host blocks ICMP packets (firewall), it will not be detected. Tools like Nmap are better suited for production scanning.

## Why I Wrote This
To understand how basic network host discovery works under the hood using core Linux utilities.
