# The Social-Engineer Toolkit (SET)
* Copyright 2020 The Social-Engineer Toolkit (SET) 
* Written by: David Kennedy (ReL1K) @HackingDave 
* Company: [TrustedSec](https://www.trustedsec.com)


## Description
The Social-Engineer Toolkit is an open-source penetration testing framework designed for social engineering. SET has a number of custom attack vectors that allow you to make a believable attack quickly. SET is a product of TrustedSec, LLC – an information security consulting firm located in Cleveland, Ohio.

DISCLAIMER: This is *only* for testing purposes and can only be used where strict consent has been given. Do not use this for illegal purposes, period.
Please read the LICENSE under readme/LICENSE for the licensing of SET. 

### Supported platforms
* Linux
* Mac OS X


## Installation
### Windows 10 WSL/WSL2 Kali Linux
```bash
sudo apt install set -y
```
Kali Linux on Windows 10 is a minimal installation so it doesn't have any tools installed.
You can easily install Social Engineer Toolkit on WSL/WSL2 without needing pip using the above command.

### Linux
```bash
git clone https://github.com/trustedsec/social-engineer-toolkit/ setoolkit/
cd setoolkit
pip3 install -r requirements.txt
python setup.py
```


## SET Tutorial
For a full document on how to use SET, [visit the SET user manual](https://github.com/trustedsec/social-engineer-toolkit/raw/master/readme/User_Manual.pdf).


## Bugs and enhancements
For bug reports or enhancements, please open an [issue](https://github.com/trustedsec/social-engineer-toolkit/issues) here.
