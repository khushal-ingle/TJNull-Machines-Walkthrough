# Nmap 7.95 scan initiated Thu Jan 29 00:11:18 2026 as: /usr/lib/nmap/nmap -v -p- -Pn -sT -sV -sC -A -O -oA beebox 10.132.176.51
Nmap scan report for 10.132.176.51
Host is up (0.0047s latency).
Not shown: 65533 closed tcp ports (conn-refused)
PORT      STATE SERVICE VERSION
53/tcp    open  domain  dnsmasq 2.51
| dns-nsid: 
|_  bind.version: dnsmasq-2.51
46888/tcp open  unknown
| fingerprint-strings: 
|   DNSStatusRequestTCP, DNSVersionBindReqTCP, GenericLines, GetRequest, HTTPOptions, Help, NULL, RPCCheck, RTSPRequest: 
|     OAFP_BB9EFA371D410A6E99AC635F720A130 
|     CPH2401
|     OnePlus
|_    iphone
1 service unrecognized despite returning data. If you know the service/version, please submit the following fingerprint at https://nmap.org/cgi-bin/submit.cgi?new-service :
SF-Port46888-TCP:V=7.95%I=7%D=1/29%Time=697A585B%P=x86_64-pc-linux-gnu%r(N
SF:ULL,67,"\0e\x01\0\x02OAFP_BB9EFA371D410A6E99AC635F720A130\x20\r\x01\0\x
SF:02\0\0\x02\xff\xf5\x03\x03\xfe\x04'\x10\x05\0\n\x06\x07CPH2401\x07\x07O
SF:nePlus\x08\x06iphone\n\x08\x0b\x01\x0c\x13\r\x01\x0eN\xf5\x95B\x19\+\0\
SF:0")%r(GenericLines,67,"\0e\x01\0\x02OAFP_BB9EFA371D410A6E99AC635F720A13
SF:0\x20\r\x01\0\x02\0\0\x02\xff\xf5\x03\x03\xfe\x04'\x10\x05\0\n\x06\x07C
SF:PH2401\x07\x07OnePlus\x08\x06iphone\n\x08\x0b\x01\x0c\x13\r\x01\x0eN\xf
SF:5\x95B\x19\+\0\0")%r(GetRequest,67,"\0e\x01\0\x02OAFP_BB9EFA371D410A6E9
SF:9AC635F720A130\x20\r\x01\0\x02\0\0\x02\xff\xf5\x03\x03\xfe\x04'\x10\x05
SF:\0\n\x06\x07CPH2401\x07\x07OnePlus\x08\x06iphone\n\x08\x0b\x01\x0c\x13\
SF:r\x01\x0eN\xf5\x95B\x19\+\0\0")%r(HTTPOptions,67,"\0e\x01\0\x02OAFP_BB9
SF:EFA371D410A6E99AC635F720A130\x20\r\x01\0\x02\0\0\x02\xff\xf5\x03\x03\xf
SF:e\x04'\x10\x05\0\n\x06\x07CPH2401\x07\x07OnePlus\x08\x06iphone\n\x08\x0
SF:b\x01\x0c\x13\r\x01\x0eN\xf5\x95B\x19\+\0\0")%r(RTSPRequest,67,"\0e\x01
SF:\0\x02OAFP_BB9EFA371D410A6E99AC635F720A130\x20\r\x01\0\x02\0\0\x02\xff\
SF:xf5\x03\x03\xfe\x04'\x10\x05\0\n\x06\x07CPH2401\x07\x07OnePlus\x08\x06i
SF:phone\n\x08\x0b\x01\x0c\x13\r\x01\x0eN\xf5\x95B\x19\+\0\0")%r(RPCCheck,
SF:67,"\0e\x01\0\x02OAFP_BB9EFA371D410A6E99AC635F720A130\x20\r\x01\0\x02\0
SF:\0\x02\xff\xf5\x03\x03\xfe\x04'\x10\x05\0\n\x06\x07CPH2401\x07\x07OnePl
SF:us\x08\x06iphone\n\x08\x0b\x01\x0c\x13\r\x01\x0eN\xf5\x95B\x19\+\0\0")%
SF:r(DNSVersionBindReqTCP,67,"\0e\x01\0\x02OAFP_BB9EFA371D410A6E99AC635F72
SF:0A130\x20\r\x01\0\x02\0\0\x02\xff\xf5\x03\x03\xfe\x04'\x10\x05\0\n\x06\
SF:x07CPH2401\x07\x07OnePlus\x08\x06iphone\n\x08\x0b\x01\x0c\x13\r\x01\x0e
SF:N\xf5\x95B\x19\+\0\0")%r(DNSStatusRequestTCP,67,"\0e\x01\0\x02OAFP_BB9E
SF:FA371D410A6E99AC635F720A130\x20\r\x01\0\x02\0\0\x02\xff\xf5\x03\x03\xfe
SF:\x04'\x10\x05\0\n\x06\x07CPH2401\x07\x07OnePlus\x08\x06iphone\n\x08\x0b
SF:\x01\x0c\x13\r\x01\x0eN\xf5\x95B\x19\+\0\0")%r(Help,67,"\0e\x01\0\x02OA
SF:FP_BB9EFA371D410A6E99AC635F720A130\x20\r\x01\0\x02\0\0\x02\xff\xf5\x03\
SF:x03\xfe\x04'\x10\x05\0\n\x06\x07CPH2401\x07\x07OnePlus\x08\x06iphone\n\
SF:x08\x0b\x01\x0c\x13\r\x01\x0eN\xf5\x95B\x19\+\0\0");
MAC Address: 5E:E6:04:85:54:5F (Unknown)
Device type: phone
Running: Google Android 10.X, Linux 4.X
OS CPE: cpe:/o:google:android:10 cpe:/o:linux:linux_kernel:4
OS details: Android 9 - 10 (Linux 4.9 - 4.14)
Uptime guess: 20.858 days (since Thu Jan  8 03:39:01 2026)
Network Distance: 1 hop
TCP Sequence Prediction: Difficulty=259 (Good luck!)
IP ID Sequence Generation: All zeros

TRACEROUTE
HOP RTT     ADDRESS
1   4.74 ms 10.132.176.51

Read data files from: /usr/share/nmap
OS and Service detection performed. Please report any incorrect results at https://nmap.org/submit/ .
# Nmap done at Thu Jan 29 00:13:56 2026 -- 1 IP address (1 host up) scanned in 158.19 seconds
