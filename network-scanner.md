A network scanner written in Python 3 using the Scapy module.
### Features - Scans the entire subnet and returns the IP addresses and MAC addresses of all devices on the network
 - Or scan a single IP address and returns the MAC address
### Tech* [Python 3]
### Source Code

[network-scanner.txt](https://github.com/vestyr/hello-world/files/7117916/network-scanner.txt)

### Installation
Requires [Python 3]
Install the dependencies and devDependencies  run.
$ mkdir network_scanner
$ cd network_scanner
$ touch app.py
Copy the source code and paste it into app.py
$ python3 -m venv venv
$ source venv/bin/activate
$ (venv) pip3 install scapy
For the entire subnet
$ (venv) python3 app.py -t <Router IP>/24
Or for a specific device
$  (venv) python3 app.py -t <Device IP>
----
