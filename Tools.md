<h1>Tools</h1>

NMAP - tool used for network discovery (enumeration). Find devices on network, check open/closed ports on target, services, OS version, vulnerability scanning, firewall detection, etc.
* ex: nmap --script=(script name) -Pn -sX -p1-999 (IP address)
* --script vuln - scans vulnerabilities
* -p- - scans all ports
* -T(0-5) - timing template. 0-5 slowest to fastest. Can speed up nmap.
* -sV - probe open ports to determine service/version info

Elastic - cybersecurity threat detection, investigation, and response platform
* learned how to filter for specific events and information
* can use KQL (Kibana Query Language) to search

Splunk - data platform that collects, indexes, and analyzes machine-generated data to provide insights on security, it operations, business analytics
* index=(database) - search a specific database or even logs. can put * to search all databases and event logs
* *(value)* - wildcard search. Match text anywhere within a field value

CyberChef - simple and complex data manipulation
* decode encoded data

CrackStation - Password Hash Cracker

Atomic Red - collection of red team test cases that can be executed to test for detection gaps
* if you want to run on linux and mac install PowerShell Core
* invoke-atomictest (technique) - used to execute atomic red team test
* parameters:
  -ShowDetails: shows details of each test
  -Checkprereq: check that all required resources are in place
  -testnumbers (# of test): specify which test you want done
  -cleanup: clean up artifacts from the test

Event Viewer - Windows tool that displays information about significant events happening on computer

Burp Suite - Web application security testing and penetration testing. Intercepting, analyzing and modifying network traffic
* Set up intercepting and modifying website requests:
  * Settings -> Allow Brup's browser to run without a sandbox
  * Proxy -> Intercept -> Open Browser
  * In browser -> browse website
  * If website doesn't load change settings -> proxy -> request interception rule (all check) -> response interception rule (all check)
  * Proxy -> HTTP History
  * Find request to exploit -> send to repeater -> edit request -> Send
  * If you want to repeat exploit multiple times:
  * in request code box press ctrl+r how many times you want to execute exploit
  * click + icon and create tab group
  * send group sequence(one at a time) or parallel (at same time)

YARA - Tool used to identify and classify malware based on patterns in its code. Done by writing custom rules to scan for specific characteristics like particular strings, file headers, or behaviours.

Floss - Tool that extracts obfuscated strings from program
* floss.exe (file path) - runs floss on file
* can pipe results to a txt file

CloudWatch - Monitors applications at multiple levels in AWS environment

CloudTrail - Monitors actions in AWS environment

JQ - transform and filter JSON data to be more understandable
* jq '(what to filter by)' file
* can pipe to filter more

msfvenom - generate payload and encoding it to evade detection

nc - reads and write to network conection using TCP or UDP (network listener). Can be used to connect a reverse shell.

Risk Assessment - identify potential problems before they happen

Group Policy Management Editor - allows administrators to enforce policies across domain
* open with windows + r -> gpmc.msc

Azure - secure, detect, prevent, and respond to threats across cloud and on premise environments

PEStudio - software to investigate potentially malicious files and extract information from them without execution
* footprints - sections represent a memory space with different content of the executable
* indicators - shows potential indicators like URLs or other suspicious attributes

ILSpy - decompiles code so it's readable

Kubernetes - container orchestration system
* creates containers for microservices to balance the traffic coming in

Minikube - tool that runs a single node Kubernetes cluster on local machine for development and testing purposes
* minikube start - start minikube

pdftotext - convet pdf file to text file
* pdftotext (pdf file) -upw (Password)

exploit-db - public vulnerability database

enum4linux - enumerate SMB shares on linuc and windows systems
* enum4linux (options) (IP)

pentestmonkey.net - used to look for privilege escalation vectors on window systems. ex: php-reverse-shell

smbclient - allows user to access and manage files and resources on SMB server
