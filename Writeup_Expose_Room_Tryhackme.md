Write up about the expose room. This room is available at: https://tryhackme.com/room/expose

written by: Enrico Acquaviva


First: Let's use Nmap to scan all ports, in this case, I don't need to be stealthy so let's use -T4 like in a CTF but, because I do not need to be quick, I will scan all ports using -p-. I also add the -sv parameter to determine service/version info on open ports.

nmap -sV -T4 10.10.83.24 -p-

