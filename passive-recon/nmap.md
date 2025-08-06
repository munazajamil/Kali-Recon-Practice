- Tool: Nmap

-  Purpose:
  
Nmap is a network mapper used for active scanning to find live hosts, open ports, services, and OS info.

- Command Used:

nmap -sS -sV -T4 certifiedhacker.com
nmap -A certifiedhacker.com
nmap -sV certifiedhacker.com
NMAP -Os certifiedhacker.com

-  Output:
  
Port 22: SSH (Open)
Port 80: HTTP (Apache 2.4)
Port 443: HTTPS

-  Screenshots:
  Already added in the folder

💡 Notes
This helped me understand which services were exposed and running on the target host. I performed -A (aggresive scan) and few other to see the results given by nmap.
