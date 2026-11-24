
nmap -sn 192.168.1.0/24 [ Local OS cmd: ip a ]
sudo netdiscover -r 192.168.1.0/24
sudo arp-scan -l

nmap -sV -A -T4 -O -p- 192.168.1.104
nmap -v -p- -Pn -sT -sV -sC -A -O 192.168.1.104 -oA kioptrix1 | ccze -A
nmap output
Port	Service	Version	Priority
22	SSH	OpenSSH 2.9p2	Medium
80	HTTP	Apache 1.3.20	High
111	RPC	rpcbind 2	Medium
139	SMB	Samba	High
443	HTTPS	Apache 1.3.20 / mod_ssl 2.8.4	Very High
32768	RPC Status	status 1	Medium


<img width="866" height="184" alt="image" src="https://github.com/user-attachments/assets/5aa776ee-2e7c-4e30-858b-f3923212390f" />

<img width="785" height="673" alt="image" src="https://github.com/user-attachments/assets/9ea6bf6d-6150-430d-9aad-9cb2701a9a81" />


<img width="703" height="801" alt="image" src="https://github.com/user-attachments/assets/0e6a5919-7fe3-429e-9787-10a503692b11" />
