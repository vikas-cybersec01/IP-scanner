# IP-scanner
Basic IP scanner using bash ping loop. Learning project.   

#What I learned 
- Bash for loops 
- Commands substitution $(seq)
- grep filterin
- cut & tr for parsing
- Background process (&)

##Usage

./ip_test.sh 

##Limitation 
Only uses ICMP ping. If target blocks ICMP, it won't detect. Nmap is better for production.

## Why I Wrote This
To understand how network scanners work at the lowest level.
