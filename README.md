In kali console execute the ping sweeper via './ipsweep.sh 192.168.1' or whatever first 3 bytes of the IP address you want to sweep

You can output this information into the file by using the '>' 
eg. ./ipsweep.sh 192.168.181 > ip.txt

This will output all the ip addresses of the devices that give an ICMP response from 192.168.181.1 to 192.168.181.254

First IP address is reserved as the network IP and the last address is reserved for the broadcast address thats why we only sweep from 1 to 254.
