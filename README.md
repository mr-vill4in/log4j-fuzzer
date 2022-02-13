# log4j-fuzzer
## For Single Target 
```bash
chmod +x log4j
```
After That Command Simply Put Your Target 
```bash
./log4j [YOUR_TARGET_URL] [YOUR_REMOTE_SERVER]
```
## For Multiple Target 
**Gether All Domain, Subdomain, Directroty in a list**
After That Simply Command This 

```bash
chmod +x log4j
```
You Can Create a remote server With https://github.com/projectdiscovery/interactsh or else try `DNSLOG.CN` this 

```bash
cat [put_your_list_name_here.txt] | while read line ; do ./log4j $line [YOUR_Remote_Server_IP/URL_HERE] ;done
```

