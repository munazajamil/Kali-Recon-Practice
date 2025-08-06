- Tool: Gobuster & dirb
Type - Active recon

- Purpose:
Gobuster & dirb is used for brute-force scanning of hidden directories and files on websites.

-  Command Used:

gobuster dir -u http://example.com -w /usr/share/wordlists/dirb/common.txt
dirb -h certifiedhacker.com


- Output:
  
Found hidden directories: like
/admin
/backup
/uploads
/css
and many more.


- Screenshot already added

- Note:
It exposed unlisted directories that could be potential entry points for attackers.
