# HVAC Traces
This repository contains pcap traces of the HVAC system of a university. Its goal is to provide the research
community interested in automation system security with real network traffic to evaluate, validate Network Intrustion Detection System 

For privacy sake, the IP addresses have been anonymized with [Crypto-PAN](https://www.cc.gatech.edu/computing/Telecomm/projects/cryptopan/) and the packet payload have been truncated.

### IP Addresses of Interest

| IP Addresses 		| Component Type 	|
|-------------------|------------------	|
|252.103.119.187	|	Gateway		 	|
|252.103.119.36		|	Control Server	|
|252.103.119.173	|	S7 Client		|
|252.103.119.156	|	S7 Server		|
|252.103.120.7		|	HMI				|
|252.103.120.20		|	HMI				|
|252.103.120.30		|	HMI				|
|252.103.119.185	|	HMI				|
|252.103.119.175	|	HMI				|
|252.103.120.18		|	Gateway			|
|252.103.120.15		|	Gateway			|
|252.103.120.8		| 	Gateway			|
|252.103.120.13		|	Gateway			|
|252.103.120.169	| 	Gateway			|
|252.103.120.48		|	HMI				|
|252.103.120.14		|	Gateway			|
|252.103.120.9		|	Gateway			|
|252.103.117.244	|	Gateway			|
|252.103.119.160	|	Netbios Node	|
|206.120.97.255		| 	Broadcast IP	|
|252.103.120.32		|	Netbios Node 	|
|136.253.241		|	DNS Server		|
|133.136.250.44		|	Update Server	|	
|252.103.120.22		|	HMI				|
|252.103.120.172	|	Netbios Node	|
|252.103.120.10		|	Netbios Node	|
|208.103.225.198	| 	SSDP Multicast	|
|133.136.250.40		|	Update Server	|
|114.185.182.52		| 	NTP Server		|
|252.103.107.188	|	Netbios Node	|
|252.103.120.34		| 	Netbios Node	|
|252.103.120.33		| 	Netbios Node	|
|252.102.233.48		| 	HTTP Server		|


### Uncommon Ports 

| Port number		|	Protocol		|
|-------------------|-------------------|
| 50540				|	DCE/RPC			|
| 54540				|	DCE/RPC			|
| 55844				|	DCE/RPC			|
| 49885				|	DCE/RPC			|
| 58658				|	DCE/RPC			|
| 56427				|	DCE/RPC			|
| 62868				|	DCE/RPC			|
| 59303				|	DCE/RPC			|
| 53566				|	DCE/RPC			|
| 50000				|	Proprietary		|
| 2499				|	Proprietary		|
| 889				|   Update via HTTP	|


You can find the traces here [traces](https://drive.google.com/open?id=1iuSKJb5h__aQ2f41-fdz9e_yxYMV7cM6)
