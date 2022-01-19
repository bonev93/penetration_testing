# FOOTPRINTING TASKS

## Traceroute to few websites by your choice

1. unibit.bg

```
command: traceroute unibit.bg

output:
traceroute to unibit.bg (194.141.8.30), 64 hops max, 52 byte packets
 1  192.168.0.1 (192.168.0.1)  3.062 ms  2.796 ms  1.873 ms
 2  dsldevice.lan (192.168.1.1)  3.581 ms  23.380 ms  10.219 ms
 3  87-243-116-2.ip.btc-net.bg (87.243.116.2)  6.114 ms  3.977 ms  3.990 ms
 4  * * *
 5  212-39-69-100.ip.btc-net.bg (212.39.69.100)  9.601 ms  4.102 ms  5.246 ms
 6  212-39-66-10.ip.btc-net.bg (212.39.66.10)  4.233 ms  4.957 ms  6.055 ms
 7  85.14.2.93 (85.14.2.93)  4.413 ms  4.670 ms  8.530 ms
 8  194.12.254.214 (194.12.254.214)  25.576 ms  5.809 ms
    acad-evolink.evolink.net (194.12.255.50)  4.542 ms
 9  unibit-sofia-core.lines.acad.bg (194.141.252.162)  4.592 ms  4.924 ms  5.031 ms
```

2. google.de

```
command: traceroute google.de

output:
traceroute to google.de (172.217.169.99), 64 hops max, 52 byte packets
 1  192.168.0.1 (192.168.0.1)  3.822 ms  1.891 ms  2.050 ms
 2  dsldevice.lan (192.168.1.1)  3.637 ms  2.673 ms  3.818 ms
 3  87-243-116-2.ip.btc-net.bg (87.243.116.2)  5.003 ms  3.878 ms  4.164 ms
 4  * * *
 5  * 212-39-69-110.ip.btc-net.bg (212.39.69.110)  6.491 ms  8.174 ms
 6  212-39-66-222.ip.btc-net.bg (212.39.66.222)  4.067 ms  4.460 ms  4.777 ms
 7  * * *
 8  142.251.52.80 (142.251.52.80)  4.819 ms
    216.239.47.152 (216.239.47.152)  5.978 ms
    142.251.52.84 (142.251.52.84)  9.770 ms
 9  216.239.49.217 (216.239.49.217)  4.940 ms  4.325 ms
    216.239.49.199 (216.239.49.199)  14.260 ms
10  sof02s31-in-f3.1e100.net (172.217.169.99)  4.051 ms  3.417 ms  4.022 ms
```

## DNS Lookup for ULSIT(UniBit)

```
command: nslookup unibit.bg

output:
Server: 192.168.0.1
Address: 192.168.0.1#53

Non-authoritative answer:
Name: unibit.bg
Address: 194.141.8.30
```

==================================

```
command: dig unibit.bg

output:
; <<>> DiG 9.10.6 <<>> unibit.bg
;; global options: +cmd
;; Got answer:
;; ->>HEADER<<- opcode: QUERY, status: NOERROR, id: 56997
;; flags: qr rd ra; QUERY: 1, ANSWER: 1, AUTHORITY: 0, ADDITIONAL: 0

;; QUESTION SECTION:
;unibit.bg. IN A

;; ANSWER SECTION:
unibit.bg. 85779 IN A 194.141.8.30

;; Query time: 11 msec
;; SERVER: 192.168.0.1#53(192.168.0.1)
;; WHEN: Wed Jan 19 23:23:04 EET 2022
;; MSG SIZE rcvd: 43
```

================================
WHOIS Lookup for ULSIT(UniBit)

```
command: whois unibit.bg

output:
% IANA WHOIS server
% for more information on IANA, visit http://www.iana.org
% This query returned 1 object

refer: whois.register.bg

domain: BG

organisation: Register.BG
address: 40, Slivnitsa blvd
address: Varna 9000
address: Bulgaria

contact: administrative
name: Dragomir Slavov
organisation: Register.BG
address: 40, Slivnitsa blvd
address: Varna 9000
address: Bulgaria
phone: +359 52 702562
fax-no: +359 52 702561
e-mail: dhs@digsys.bg

contact: technical
name: Daniel Kalchev
organisation: Register.BG
address: 40, Slivnitsa blvd
address: Varna 9000
address: Bulgaria
phone: +359 52 702563
fax-no: +359 52 702561
e-mail: daniel@digsys.bg

nserver: A.NIC.BG 192.92.129.99 2a02:6a80:0:0:192:92:129:99
nserver: B.NIC.BG 193.68.3.232 2a02:6a80:0:0:193:68:3:232
nserver: C.NIC.BG 193.68.99.99 2a02:6a80:0:0:193:68:99:99
nserver: D.NIC.BG 194.0.32.1 2001:678:3c:0:0:0:0:1
nserver: E.NIC.BG 185.143.80.1 2a02:6a80:530e:0:0:0:0:1
nserver: P.NIC.BG 2001:500:14:6110:ad:0:0:1 204.61.216.110
ds-rdata: 58606 8 2 305151ebb808cfa54a262403982d4c27e081b1c4accdad4b4d83ce091188b1a0

whois: whois.register.bg

status: ACTIVE
remarks: Registration information: http://www.register.bg

created: 1995-01-03
changed: 2021-02-24
source: IANA

DOMAIN NAME: unibit.bg (unibit.bg)
registration status: busy, active

NAME SERVER INFORMATION:
ns1.unibit.bg 185.136.96.77 2a06:fb00:1::1:77
ns2.unibit.bg 185.136.97.77 2a06:fb00:1::2:77
ns3.unibit.bg 185.136.98.77 2a06:fb00:1::3:77
ns4.unibit.bg 185.136.99.77 2a06:fb00:1::4:77

DNSSEC: inactive

According to REGULATION (EU) 2016/679 OF THE EUROPEAN PARLIAMENT AND
OF THE COUNCIL (GDPR) personal data is not published.

If you would like to contact the persons responsible for the domain
name, please, use the online WHOIS contact form from the "Info / Whois" menu
at www.register.bg.
```

extra mile I added in this section for practice purposes (thanks to Pavel's first lecture)

get a set of @unibit.bg mails

1. fire up kali linux and msfconsole

<img width="892" alt="Screen Shot 2022-01-20 at 0 43 07" src="https://user-images.githubusercontent.com/18306338/150230961-f1fc52b4-a9d5-4cda-9fa8-5fc7c08d25da.png">

2. search email gather

<img width="813" alt="Screen Shot 2022-01-20 at 0 45 00" src="https://user-images.githubusercontent.com/18306338/150231026-4e92fe3a-f411-4b24-83ef-90ad361ffa88.png">

3. use the auxiliary/gather/search_email_collector and query available options

<img width="574" alt="Screen Shot 2022-01-20 at 0 50 34" src="https://user-images.githubusercontent.com/18306338/150231193-3aa2e363-d38a-425d-b250-1b4172f1bd35.png">

4. set domain as unibit.bg and output file as mails.txt

<img width="524" alt="Screen Shot 2022-01-20 at 0 50 54" src="https://user-images.githubusercontent.com/18306338/150231204-bed205be-61f8-4c97-83b9-8045a426d29e.png">

6. run (won't be uploading the txt file as this repo will be public)


================================

# WEBENUMERATION TASKS

## Check robots.txt and sitemap.xml for ULSIT and DVWA

1. unibit robots.txt

<img width="670" alt="unibit_robot" src="https://user-images.githubusercontent.com/18306338/150217478-ac38b8e2-d6b5-495d-b9ea-5bfe4a0dc15a.png">

2. unibit sitemap.xml

<img width="975" alt="unibit_sitemap" src="https://user-images.githubusercontent.com/18306338/150217770-304bf069-74c4-4203-a11b-413183cec22c.png">

3. dvwa robots.txt

<img width="591" alt="dvwa_robots" src="https://user-images.githubusercontent.com/18306338/150219483-feb49ded-4947-4991-b43f-cc6e3aaa0404.png">

4. dvwa sitemap.xml

<img width="713" alt="dvwa_sitemap" src="https://user-images.githubusercontent.com/18306338/150219884-bcbfb2ad-f42a-4923-ae2c-90099887d465.png">

## Use ffuf or gobuster to enumerate DVWA’s pages

## Find DVWA’s source code

# Burp&Zap tasks

Not included in report: Configure FoxyProxy for Burp and ZAP
NOTE: Make sure you use the correct ports
Not included in report: Play around with Burp’s repeater
Try using ZAP’s automated scanner against DVWA (screenshot)
Extra Mile: Try using ZAP’s automated scan while authenticated against DVWA (methodology and screenshot)

Vulnerability research:
Look for the EternalBlue vulnerability
What is the CVE number of this vulnerability?
What software does it affect?
What is the CVSS score of the vulnerability?
What protocol is being exploited?
Look for DirtyCow vulnerability
What is the CVE number of this vulnerability?
What software does it affect?
What is the CVSS score of the vulnerability?
What is the vulnerability type?
Extra Mile: Look for CVE-2009-1358
What software does it affect?
What is the CVSS score of the vulnerability?
What protocol is being exploited?
