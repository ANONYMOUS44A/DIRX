## DIRX

![image](https://github.com/RAPS-LAUNCHER/DIRX/assets/142556460/8a8d6ac3-85ee-48fd-b04a-db5024654244)

![image](https://github.com/RAPS-LAUNCHER/DIRX/assets/142556460/5b7dfb82-a56e-4a60-8961-2c0677d9bd81)

INSTALLATION
```
cd && (apt update || pkg update) && (apt upgrade || pkg upgrade) && (apt install git || pkg install git) && git clone https://github.com/RAPS-LAUNCHER/DIRX.git && cd DIRX && chmod +x * && ./dirx
```

USAGE
```
dirx -u <target_url> -w <wordlist_path> [-f] [-v]
```
EXAMPLES:
```
 dirx -u https://exemple.com -w wordlist.txt
 dirx -u https://exemple.com -w wordlist.txt -f
 dirx -v
```
