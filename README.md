# Spaghetti - Web Application Security Scanner
![version](https://img.shields.io/badge/version-v0.1.3-green.svg) ![python](https://img.shields.io/badge/python-2.7-green.svg)  ![license](https://img.shields.io/badge/License-GPLv3-brightgreen.svg)

Spaghetti is an Open Source web application scanner, it is designed to find various default and insecure files, configurations, and misconfigurations.
Spaghetti is built on python2.7 and can run on any platform which has a Python environment.

![logo](https://i.imgur.com/sLETEV2.png)

## Installation
```
$ git clone https://github.com/m4ll0k/Spaghetti.git
$ cd Spaghetti 
$ pip install -r requirements.txt
$ python spaghetti.py
```
## Features
- Fingerprints
  - Server
  - Web Frameworks (CakePHP,CherryPy,...)
  - Web Application Firewall (Waf)
  - Content Management System (CMS)
  - Operating System (Linux,Unix,..)
  - Language (PHP,Ruby,...)
  - Cookie Security

- Discovery:

  - Bruteforce
    - Admin Interface
    - Common Backdoors
    - Common Backup Directory
    - Common Backup File
    - Common Directory
    - Common File
    - Log File
  
  - Disclosure
    - Emails
    - Private IP
    - Credit Cards
  
  - Attacks
    - HTML Injection
    - SQL Injection
    - LDAP Injection
    - XPath Injection
    - Cross Site Scripting (XSS)
    - Remote File Inclusion (RFI)
    - PHP Code Injection
    
  - Other
    - HTTP Allow Methods
    - HTML Object
    - Multiple Index
    - Robots Paths
    - Web Dav
    - Cross Site Tracing (XST)
    - PHPINFO
    - .Listing
    
  - Vulns
    - ShellShock
    - Anonymous Cipher (CVE-2007-1858)
    - Crime (SPDY) (CVE-2012-4929)
    - Struts-Shock


## Example
`python spaghetti --url site.com --scan 0 --random-agent --verbose`

![img1](https://i.imgur.com/BCrrWNt.png)
![img2](https://i.imgur.com/kRRN6G4.png)
