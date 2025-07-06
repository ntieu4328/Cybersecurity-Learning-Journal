<h1>Processes</h1>

Enumeration:
* nmap the IP to look for open ports and versions of them
* `nmap -sP (IP)/24` - ping scan devices on network
 * can find network ip with cmd -> ipconfig -> default gateway or ip route
* unknown or Amazon devices can be personal important devices

Iphone
* `nmap -sP (IP)/24` - shows unknown or amazon devices
* `nmap -sS (IP)/24` - shows iphone sync port

Enumeration of website:
* gobuster website to look for directories
* Look up vulnerabilities of what is powering website icluding version of it
* can also see if open ports give you anything in search bar
  * ex: (IP):(port)
