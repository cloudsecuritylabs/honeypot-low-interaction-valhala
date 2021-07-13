# honeypot-low-interaction-valhala
download valhala-180 english verison
https://sourceforge.net/projects/valhalahoneypot/files/valhalahoneypot/valhala180/

1. extract file
2. disable Windows Defender Firewall
3. Turn of telnel service on windows
4. Click on Valhala Honeypot to open the low interaction honeypot
5. click on server config
6. click on FTP Server, create a folder c://valhala and enable FTP hooney service, update username and pass as "user/user" (or whatever you like to use)
7. Click on POP3 server, enable pop3 service, update username password (user/user)
8. click on monitor

Test ftp honey service
======
open up command prompt
- telnet 127.0.0.1 21
- USER user
- PASS user


Test pop3 honey service
======
open up command prompt
- telnet 127.0.0.1 110
- USER user
- PASS user
