# useful-bash-commands (For Mac)

Tired of always googling commands for tasks (e.g., check if port is open)? A cheatsheet is all you need!

## Local Port Scanning (Check if a port on the local machine is occupied)
``sudo lsof -i -n -P | grep YOUR_PORT_NUMBER``

## LAN Port Scanning (Check if a port on a specific local host is occupied)
``nmap -Pn -p PORT_NUMBER 192.168.1.0/24 | grep HOST_NAME``


## Capture Packets Using Tcpdump
``tcpdump -i any -w PCAP_FILE_PATH host HOST_IP``
