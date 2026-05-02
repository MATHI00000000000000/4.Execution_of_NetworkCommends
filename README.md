# 4.Execution_of_NetworkCommands
## AIM :Use of Network commands in Real Time environment
## Software : Command Prompt And Network Protocol Analyzer
## Procedure: To do this EXPERIMENT- follows these steps:
<BR>
In this EXPERIMENT- students have to understand basic networking commands e.g cpdump, netstat, ifconfig, nslookup ,traceroute and also Capture ping and traceroute PDUs using a network protocol analyzer 
<BR>
All commands related to Network configuration which includes how to switch to privilege mode
<BR>
and normal mode and how to configure router interface and how to save this configuration to
<BR>
flash memory or permanent memory.
<BR>
This commands includes
<BR>
• Configuring the Router commands
<BR>
• General Commands to configure network
<BR>
• Privileged Mode commands of a router 
<BR>
• Router Processes & Statistics
<BR>
• IP Commands
<BR>
• Other IP Commands e.g. show ip route etc.
<BR>

## Output
```
IPCONFIG
Windows IP Configuration


Ethernet adapter Ethernet:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

Ethernet adapter Ethernet 2:

   Connection-specific DNS Suffix  . :
   Link-local IPv6 Address . . . . . : fe80::174a:ab1e:9489:5445%2
   IPv4 Address. . . . . . . . . . . : 192.168.56.1
   Subnet Mask . . . . . . . . . . . : 255.255.255.0
   Default Gateway . . . . . . . . . :

Wireless LAN adapter Local Area Connection* 1:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

Wireless LAN adapter Local Area Connection* 2:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

Wireless LAN adapter Wi-Fi:

   Connection-specific DNS Suffix  . :
   IPv6 Address. . . . . . . . . . . : 2409:40f4:9:945e:a8f3:e839:229b:e58b
   Temporary IPv6 Address. . . . . . : 2409:40f4:9:945e:39d0:45dd:702b:d1db
   Link-local IPv6 Address . . . . . : fe80::9f1d:9128:68dc:85e1%11
   IPv4 Address. . . . . . . . . . . : 10.236.192.252
   Subnet Mask . . . . . . . . . . . : 255.255.255.0
   Default Gateway . . . . . . . . . : fe80::947f:c3ff:fe04:e907%11
                                       10.236.192.54
 IPCONFIG/ALL
 Windows IP Configuration

   Host Name . . . . . . . . . . . . : TMP215-75-G2
   Primary Dns Suffix  . . . . . . . :
   Node Type . . . . . . . . . . . . : Hybrid
   IP Routing Enabled. . . . . . . . : No
   WINS Proxy Enabled. . . . . . . . : No

Ethernet adapter Ethernet:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :
   Description . . . . . . . . . . . : Realtek PCIe GbE Family Controller
   Physical Address. . . . . . . . . : 74-D4-DD-CF-7F-19
   DHCP Enabled. . . . . . . . . . . : Yes
   Autoconfiguration Enabled . . . . : Yes

Ethernet adapter Ethernet 2:

   Connection-specific DNS Suffix  . :
   Description . . . . . . . . . . . : VirtualBox Host-Only Ethernet Adapter
   Physical Address. . . . . . . . . : 0A-00-27-00-00-02
   DHCP Enabled. . . . . . . . . . . : No
   Autoconfiguration Enabled . . . . : Yes
   Link-local IPv6 Address . . . . . : fe80::174a:ab1e:9489:5445%2(Preferred)
   IPv4 Address. . . . . . . . . . . : 192.168.56.1(Preferred)
   Subnet Mask . . . . . . . . . . . : 255.255.255.0
   Default Gateway . . . . . . . . . :
   DHCPv6 IAID . . . . . . . . . . . : 755630119
   DHCPv6 Client DUID. . . . . . . . : 00-01-00-01-30-49-C3-17-74-D4-DD-CF-7F-19
   NetBIOS over Tcpip. . . . . . . . : Enabled

Wireless LAN adapter Local Area Connection* 1:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :
   Description . . . . . . . . . . . : Microsoft Wi-Fi Direct Virtual Adapter
   Physical Address. . . . . . . . . : FC-6D-77-99-CA-BA
   DHCP Enabled. . . . . . . . . . . : Yes
   Autoconfiguration Enabled . . . . : Yes

Wireless LAN adapter Local Area Connection* 2:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :
   Description . . . . . . . . . . . : Microsoft Wi-Fi Direct Virtual Adapter #2
   Physical Address. . . . . . . . . : FE-6D-77-99-CA-B9
   DHCP Enabled. . . . . . . . . . . : Yes
   Autoconfiguration Enabled . . . . : Yes

Wireless LAN adapter Wi-Fi:

   Connection-specific DNS Suffix  . :
   Description . . . . . . . . . . . : Intel(R) Wi-Fi 6E AX211 160MHz
   Physical Address. . . . . . . . . : FC-6D-77-99-CA-B9
   DHCP Enabled. . . . . . . . . . . : Yes
   Autoconfiguration Enabled . . . . : Yes
   IPv6 Address. . . . . . . . . . . : 2409:40f4:9:945e:a8f3:e839:229b:e58b(Preferred)
   Temporary IPv6 Address. . . . . . : 2409:40f4:9:945e:39d0:45dd:702b:d1db(Preferred)
   Link-local IPv6 Address . . . . . : fe80::9f1d:9128:68dc:85e1%11(Preferred)
   IPv4 Address. . . . . . . . . . . : 10.236.192.252(Preferred)
   Subnet Mask . . . . . . . . . . . : 255.255.255.0
   Lease Obtained. . . . . . . . . . : 02 May 2026 13:21:08
   Lease Expires . . . . . . . . . . : 02 May 2026 14:51:17
   Default Gateway . . . . . . . . . : fe80::947f:c3ff:fe04:e907%11
                                       10.236.192.54
   DHCP Server . . . . . . . . . . . : 10.236.192.54
   DHCPv6 IAID . . . . . . . . . . . : 184315255
   DHCPv6 Client DUID. . . . . . . . : 00-01-00-01-30-49-C3-17-74-D4-DD-CF-7F-19
   DNS Servers . . . . . . . . . . . : 10.236.192.54
                                       2409:40f4:9:945e::bb
   NetBIOS over Tcpip. . . . . . . . : Enabled
   IPCONFIG/RELEASE
   Windows IP Configuration

No operation can be performed on Ethernet while it has its media disconnected.
No operation can be performed on Local Area Connection* 1 while it has its media disconnected.
No operation can be performed on Local Area Connection* 2 while it has its media disconnected.

Ethernet adapter Ethernet:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

Ethernet adapter Ethernet 2:

   Connection-specific DNS Suffix  . :
   Link-local IPv6 Address . . . . . : fe80::174a:ab1e:9489:5445%2
   IPv4 Address. . . . . . . . . . . : 192.168.56.1
   Subnet Mask . . . . . . . . . . . : 255.255.255.0
   Default Gateway . . . . . . . . . :

Wireless LAN adapter Local Area Connection* 1:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

Wireless LAN adapter Local Area Connection* 2:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

Wireless LAN adapter Wi-Fi:

   Connection-specific DNS Suffix  . :
   IPv6 Address. . . . . . . . . . . : 2409:40f4:9:945e:a8f3:e839:229b:e58b
   Temporary IPv6 Address. . . . . . : 2409:40f4:9:945e:39d0:45dd:702b:d1db
   Link-local IPv6 Address . . . . . : fe80::9f1d:9128:68dc:85e1%11
   Default Gateway . . . . . . . . . : fe80::947f:c3ff:fe04:e907%11
   IPCONFIG/RENEW
   Windows IP Configuration

No operation can be performed on Ethernet while it has its media disconnected.
No operation can be performed on Local Area Connection* 1 while it has its media disconnected.
No operation can be performed on Local Area Connection* 2 while it has its media disconnected.

Ethernet adapter Ethernet:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

Ethernet adapter Ethernet 2:

   Connection-specific DNS Suffix  . :
   Link-local IPv6 Address . . . . . : fe80::174a:ab1e:9489:5445%2
   IPv4 Address. . . . . . . . . . . : 192.168.56.1
   Subnet Mask . . . . . . . . . . . : 255.255.255.0
   Default Gateway . . . . . . . . . :

Wireless LAN adapter Local Area Connection* 1:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

Wireless LAN adapter Local Area Connection* 2:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

Wireless LAN adapter Wi-Fi:

   Connection-specific DNS Suffix  . :
   IPv6 Address. . . . . . . . . . . : 2409:40f4:9:945e:a8f3:e839:229b:e58b
   Temporary IPv6 Address. . . . . . : 2409:40f4:9:945e:39d0:45dd:702b:d1db
   Link-local IPv6 Address . . . . . : fe80::9f1d:9128:68dc:85e1%11
   IPv4 Address. . . . . . . . . . . : 10.236.192.252
   Subnet Mask . . . . . . . . . . . : 255.255.255.0
   Default Gateway . . . . . . . . . : fe80::947f:c3ff:fe04:e907%11
                                       10.236.192.54
PING GOOGLE.COM
Pinging google.com [2404:6800:4007:82f::200e] with 32 bytes of data:
Reply from 2404:6800:4007:82f::200e: time=47ms
Reply from 2404:6800:4007:82f::200e: time=62ms
Reply from 2404:6800:4007:82f::200e: time=37ms
Reply from 2404:6800:4007:82f::200e: time=45ms

Ping statistics for 2404:6800:4007:82f::200e:
    Packets: Sent = 4, Received = 4, Lost = 0 (0% loss),
Approximate round trip times in milli-seconds:
    Minimum = 37ms, Maximum = 62ms, Average = 47ms
TRACERT GOOGLE.COM
Tracing route to google.com [2404:6800:4007:82f::200e]
over a maximum of 30 hops:

1    15 ms    18 ms     5 ms  2409:40f4:9:945e::bb
2     *        *        *     Request timed out.
3   176 ms    53 ms    37 ms  2405:200:5218:21:3925::1
4    59 ms    38 ms    57 ms  2405:200:88c:1513:62::6
5     *        *        *     Request timed out.
6    91 ms    42 ms    45 ms  2405:200:801:900::1628
7     *        *        *     Request timed out.
8    44 ms    53 ms    83 ms  2404:6800:8202:4c0::1
9   358 ms    64 ms    46 ms  2404:6800:8202:4c0::1
10    56 ms    53 ms    45 ms  2404:6800:8202:4c0::1
11     *       54 ms    49 ms  2001:4860:0:1::33ca
12    58 ms    39 ms    74 ms  2001:4860:0:1::564f
13    37 ms    51 ms    59 ms  pnmaaa-be-in-x0e.1e100.net [2404:6800:4007:82f::200e]

Trace complete.
NSLOOKUP GOOGLE.COM
Server:  UnKnown
Address:  10.236.192.54

Non-authoritative answer:
Name:    google.com
Addresses:  2404:6800:4007:811::200e
          142.250.77.110
NETSTAT -A
Active Connections

Proto  Local Address          Foreign Address        State
TCP    0.0.0.0:80             TMP215-75-G2:0         LISTENING
TCP    0.0.0.0:135            TMP215-75-G2:0         LISTENING
TCP    0.0.0.0:445            TMP215-75-G2:0         LISTENING
TCP    0.0.0.0:1309           TMP215-75-G2:0         LISTENING
TCP    0.0.0.0:4343           TMP215-75-G2:0         LISTENING
TCP    0.0.0.0:4449           TMP215-75-G2:0         LISTENING
TCP    0.0.0.0:5040           TMP215-75-G2:0         LISTENING
TCP    0.0.0.0:5141           TMP215-75-G2:0         LISTENING
TCP    0.0.0.0:46760          TMP215-75-G2:0         LISTENING
TCP    0.0.0.0:49664          TMP215-75-G2:0         LISTENING
TCP    0.0.0.0:49665          TMP215-75-G2:0         LISTENING
TCP    0.0.0.0:49666          TMP215-75-G2:0         LISTENING
TCP    0.0.0.0:49667          TMP215-75-G2:0         LISTENING
TCP    0.0.0.0:49668          TMP215-75-G2:0         LISTENING
TCP    0.0.0.0:49672          TMP215-75-G2:0         LISTENING
TCP    0.0.0.0:58995          TMP215-75-G2:0         LISTENING
TCP    10.236.192.252:139     TMP215-75-G2:0         LISTENING
TCP    127.0.0.1:5141         TMP215-75-G2:53046     ESTABLISHED
TCP    127.0.0.1:9993         TMP215-75-G2:0         LISTENING
TCP    127.0.0.1:15152        TMP215-75-G2:0         LISTENING
TCP    127.0.0.1:19443        TMP215-75-G2:0         LISTENING
TCP    127.0.0.1:46753        TMP215-75-G2:0         LISTENING
TCP    127.0.0.1:46934        TMP215-75-G2:0         LISTENING
TCP    127.0.0.1:46935        TMP215-75-G2:0         LISTENING
TCP    127.0.0.1:46935        TMP215-75-G2:65088     ESTABLISHED
TCP    127.0.0.1:46936        TMP215-75-G2:0         LISTENING
TCP    127.0.0.1:46936        TMP215-75-G2:49685     ESTABLISHED
TCP    127.0.0.1:46937        TMP215-75-G2:0         LISTENING
TCP    127.0.0.1:46937        TMP215-75-G2:49687     ESTABLISHED
TCP    127.0.0.1:49669        TMP215-75-G2:49670     ESTABLISHED
TCP    127.0.0.1:49670        TMP215-75-G2:49669     ESTABLISHED
TCP    127.0.0.1:49675        TMP215-75-G2:49676     ESTABLISHED
TCP    127.0.0.1:49676        TMP215-75-G2:49675     ESTABLISHED
TCP    127.0.0.1:49678        TMP215-75-G2:49679     ESTABLISHED
TCP    127.0.0.1:49679        TMP215-75-G2:49678     ESTABLISHED
TCP    127.0.0.1:49680        TMP215-75-G2:49681     ESTABLISHED
TCP    127.0.0.1:49681        TMP215-75-G2:49680     ESTABLISHED
TCP    127.0.0.1:49682        TMP215-75-G2:49683     ESTABLISHED
TCP    127.0.0.1:49683        TMP215-75-G2:49682     ESTABLISHED
TCP    127.0.0.1:49684        TMP215-75-G2:49686     ESTABLISHED
TCP    127.0.0.1:49685        TMP215-75-G2:46936     ESTABLISHED
TCP    127.0.0.1:49686        TMP215-75-G2:49684     ESTABLISHED
TCP    127.0.0.1:49687        TMP215-75-G2:46937     ESTABLISHED
TCP    127.0.0.1:49712        TMP215-75-G2:58995     ESTABLISHED
TCP    127.0.0.1:51779        TMP215-75-G2:0         LISTENING
TCP    127.0.0.1:51780        TMP215-75-G2:0         LISTENING
TCP    127.0.0.1:51781        TMP215-75-G2:0         LISTENING
TCP    127.0.0.1:51782        TMP215-75-G2:0         LISTENING
TCP    127.0.0.1:53046        TMP215-75-G2:5141      ESTABLISHED
TCP    127.0.0.1:58995        TMP215-75-G2:49712     ESTABLISHED
TCP    127.0.0.1:58995        TMP215-75-G2:59125     ESTABLISHED
TCP    127.0.0.1:58995        TMP215-75-G2:65078     ESTABLISHED
TCP    127.0.0.1:59125        TMP215-75-G2:58995     ESTABLISHED
TCP    127.0.0.1:65078        TMP215-75-G2:58995     ESTABLISHED
TCP    127.0.0.1:65082        TMP215-75-G2:65083     ESTABLISHED
TCP    127.0.0.1:65083        TMP215-75-G2:65082     ESTABLISHED
TCP    127.0.0.1:65084        TMP215-75-G2:65085     ESTABLISHED
TCP    127.0.0.1:65085        TMP215-75-G2:65084     ESTABLISHED
TCP    127.0.0.1:65086        TMP215-75-G2:65087     ESTABLISHED
TCP    127.0.0.1:65087        TMP215-75-G2:65086     ESTABLISHED
TCP    127.0.0.1:65088        TMP215-75-G2:46935     ESTABLISHED
TCP    192.168.56.1:139       TMP215-75-G2:0         LISTENING
TCP    [::]:80                TMP215-75-G2:0         LISTENING
TCP    [::]:135               TMP215-75-G2:0         LISTENING
TCP    [::]:445               TMP215-75-G2:0         LISTENING
TCP    [::]:4343              TMP215-75-G2:0         LISTENING
TCP    [::]:4449              TMP215-75-G2:0         LISTENING
TCP    [::]:5141              TMP215-75-G2:0         LISTENING
TCP    [::]:46760             TMP215-75-G2:0         LISTENING
TCP    [::]:49664             TMP215-75-G2:0         LISTENING
TCP    [::]:49665             TMP215-75-G2:0         LISTENING
TCP    [::]:49666             TMP215-75-G2:0         LISTENING
TCP    [::]:49667             TMP215-75-G2:0         LISTENING
TCP    [::]:49668             TMP215-75-G2:0         LISTENING
TCP    [::]:49672             TMP215-75-G2:0         LISTENING
TCP    [::]:58995             TMP215-75-G2:0         LISTENING
TCP    [::1]:15161            TMP215-75-G2:0         LISTENING
TCP    [::1]:15161            TMP215-75-G2:52923     ESTABLISHED
TCP    [::1]:15161            TMP215-75-G2:53888     TIME_WAIT
TCP    [::1]:15161            TMP215-75-G2:53893     ESTABLISHED
TCP    [::1]:15161            TMP215-75-G2:59126     ESTABLISHED
TCP    [::1]:42050            TMP215-75-G2:0         LISTENING
TCP    [::1]:52923            TMP215-75-G2:15161     ESTABLISHED
TCP    [::1]:53892            TMP215-75-G2:15161     TIME_WAIT
TCP    [::1]:53893            TMP215-75-G2:15161     ESTABLISHED
TCP    [::1]:59126            TMP215-75-G2:15161     ESTABLISHED
TCP    [2409:40f4:9:945e:39d0:45dd:702b:d1db]:49411  [2603:1040:a06:6::2]:https  ESTABLISHED
TCP    [2409:40f4:9:945e:39d0:45dd:702b:d1db]:50052  g2600-14e1-001c-006d-0000-0000-0000-0000:http  CLOSE_WAIT
TCP    [2409:40f4:9:945e:39d0:45dd:702b:d1db]:51346  [2603:1046:c06:8ce::2]:https  ESTABLISHED
TCP    [2409:40f4:9:945e:39d0:45dd:702b:d1db]:51647  sb-in-xbc:5228         ESTABLISHED
TCP    [2409:40f4:9:945e:39d0:45dd:702b:d1db]:52416  lb-140-82-112-22-iad:https  ESTABLISHED
TCP    [2409:40f4:9:945e:39d0:45dd:702b:d1db]:53039  [2603:1040:a06:6::1]:https  ESTABLISHED
TCP    [2409:40f4:9:945e:39d0:45dd:702b:d1db]:53885  [64:ff9b::34a8:75a9]:https  TIME_WAIT
TCP    [2409:40f4:9:945e:39d0:45dd:702b:d1db]:53886  [64:ff9b::34a8:75a9]:https  TIME_WAIT
TCP    [2409:40f4:9:945e:39d0:45dd:702b:d1db]:53889  [64:ff9b::4e6:ab7c]:https  TIME_WAIT
TCP    [2409:40f4:9:945e:39d0:45dd:702b:d1db]:53890  [64:ff9b::4e6:ab7c]:https  TIME_WAIT
TCP    [2409:40f4:9:945e:39d0:45dd:702b:d1db]:59110  [2606:4700:9c69:782b:c0c6:488:80f7:583c]:https  ESTABLISHED
TCP    [2409:40f4:9:945e:39d0:45dd:702b:d1db]:59288  lb-140-82-113-26-iad:https  ESTABLISHED
TCP    [2409:40f4:9:945e:39d0:45dd:702b:d1db]:60127  [2606:4700:9c69:782b:c0fe:488:80f7:583c]:https  ESTABLISHED
TCP    [2409:40f4:9:945e:39d0:45dd:702b:d1db]:60394  [2606:4700:9c69:782b:c0fe:488:80f7:583c]:https  ESTABLISHED
TCP    [2409:40f4:9:945e:39d0:45dd:702b:d1db]:63236  [64:ff9b::acbc:9b19]:https  ESTABLISHED
TCP    [2409:40f4:9:945e:39d0:45dd:702b:d1db]:64405  whatsapp-cdn6-shv-02-maa5:5222  ESTABLISHED
TCP    [2409:40f4:9:945e:39d0:45dd:702b:d1db]:64500  so-in-f188:5228        ESTABLISHED
UDP    0.0.0.0:5050           *:*
UDP    0.0.0.0:5353           *:*
UDP    0.0.0.0:5353           *:*
UDP    0.0.0.0:5353           *:*
UDP    0.0.0.0:5353           *:*
UDP    0.0.0.0:5353           *:*
UDP    0.0.0.0:5353           *:*
UDP    0.0.0.0:5353           *:*
UDP    0.0.0.0:5353           *:*
UDP    0.0.0.0:5353           *:*
UDP    0.0.0.0:5355           *:*
UDP    0.0.0.0:52646          *:*
UDP    0.0.0.0:56468          *:*
UDP    0.0.0.0:60096          *:*
UDP    10.236.192.252:137     *:*
UDP    10.236.192.252:138     *:*
UDP    10.236.192.252:1900    *:*
UDP    10.236.192.252:64399   *:*
UDP    127.0.0.1:1900         *:*
UDP    127.0.0.1:60095        *:*
UDP    127.0.0.1:62793        127.0.0.1:62793
UDP    127.0.0.1:64400        *:*
UDP    192.168.56.1:137       *:*
UDP    192.168.56.1:138       *:*
UDP    192.168.56.1:1900      *:*
UDP    192.168.56.1:64398     *:*
UDP    [::]:5353              *:*
UDP    [::]:5353              *:*
UDP    [::]:5353              *:*
UDP    [::]:5353              *:*
UDP    [::]:5353              *:*
UDP    [::]:5355              *:*
UDP    [::]:52646             *:*
UDP    [::]:56468             *:*
UDP    [::1]:1900             *:*
UDP    [::1]:64397            *:*
UDP    [fe80::174a:ab1e:9489:5445%2]:1900  *:*
UDP    [fe80::174a:ab1e:9489:5445%2]:64395  *:*
UDP    [fe80::9f1d:9128:68dc:85e1%11]:1900  *:*
UDP    [fe80::9f1d:9128:68dc:85e1%11]:64396  *:*
ARP -A
Interface: 192.168.56.1 --- 0x2
Internet Address      Physical Address      Type
192.168.56.255        ff-ff-ff-ff-ff-ff     static
224.0.0.22            01-00-5e-00-00-16     static
224.0.0.251           01-00-5e-00-00-fb     static
224.0.0.252           01-00-5e-00-00-fc     static
239.255.255.250       01-00-5e-7f-ff-fa     static

Interface: 10.236.192.252 --- 0xb
Internet Address      Physical Address      Type
10.236.192.54         96-7f-c3-04-e9-07     dynamic
10.236.192.255        ff-ff-ff-ff-ff-ff     static
224.0.0.22            01-00-5e-00-00-16     static
224.0.0.251           01-00-5e-00-00-fb     static
224.0.0.252           01-00-5e-00-00-fc     static
239.255.255.250       01-00-5e-7f-ff-fa     static
255.255.255.255       ff-ff-ff-ff-ff-ff     static
```
## Result
Thus Execution of Network commands Performed 
