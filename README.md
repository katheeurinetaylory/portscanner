# Portscanner (Python)

*AKA Scanny Boi*

## Python TCP port scanner

Scan single hosts or a /24 network for open ports

**Scan host**
*Usage:* ./portscanner.py [IP address] [start port] [end port]
*Example:* ./portscanner.py 192.168.1.10 1 65535

**Scan network**
*Usage:* ./portscanner.py [network] [start port] [end port] -n
*Example:* ./portscanner.py 192.168.1 1 65535 -n

**Upcoming**
* Add UDP scanning
* Add ability to set default timeout
* Add option to output results to file
* Clean up code
cqddyqc