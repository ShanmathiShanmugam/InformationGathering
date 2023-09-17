# InformationGathering
Information Gathering Techiques

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering

## Pen Test Tools Categories: 
Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.

## DETAILED INFO:
http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

### OUTPUT:
![Screenshot 2023-09-17 021127](https://github.com/ShanmathiShanmugam/InformationGathering/assets/121243595/b2658a76-7a4a-4722-94e9-f1ff6c544b35)

## Finding IP address:
ping facebook.com.
### OUTPUT:
![image](https://github.com/ShanmathiShanmugam/InformationGathering/assets/121243595/d5590943-9bfc-4415-83ff-8218125b33d9)

## Finding Hosting Company
ip2location.com website.
### OUTPUT:
![Screenshot 2023-09-17 021256](https://github.com/ShanmathiShanmugam/InformationGathering/assets/121243595/23738b57-364b-4732-9081-7589d3ceffe6)

### HISTORY OF WEBSITE:

### OUTPUT:

![Screenshot 2023-09-17 021640](https://github.com/ShanmathiShanmugam/InformationGathering/assets/121243595/238030a2-3041-4c8d-a29d-7f5179b0bfbe)

## Webserver Fingerprinting:
### Netcat:

sudo nc example.com 80
GET / HTTP/1.1
Host: example.com
### OUTPUT:
![image](https://github.com/ShanmathiShanmugam/InformationGathering/assets/121243595/356c599d-8b2f-4bbf-81e0-e53634c86ee2)

### nmap

### OUTPUT:
![image](https://github.com/ShanmathiShanmugam/InformationGathering/assets/121243595/a0ba5b13-08b3-457e-94b2-a47670701e0f)

### Whatweb

### OUTPUT:
![image](https://github.com/ShanmathiShanmugam/InformationGathering/assets/121243595/882a9c80-6bbd-4771-991b-90f3d469d5cc)

## httprint

### OUTPUT
![image](https://github.com/ShanmathiShanmugam/InformationGathering/assets/121243595/7654dd15-9c8e-4cda-a6c3-660890f7dbcf)

## Tracing the location
TCP Traceroute-
sudo traceroute -T www.google.com
### OUTPUT:
![image](https://github.com/ShanmathiShanmugam/InformationGathering/assets/121243595/0aeba232-d26f-4378-ab90-8142be354e0a)

UDP Traceroute-
sudo traceroute -U www.google.com
### OUTPUT:
![image](https://github.com/ShanmathiShanmugam/InformationGathering/assets/121243595/f4496ad2-66c6-4222-a269-0e6f9008f11e)

ICMP Traceroute-
sudo traceroute www.google.com
### OUTPUT:
![image](https://github.com/ShanmathiShanmugam/InformationGathering/assets/121243595/88cd6be0-d047-4170-ba13-8659986ab569)

## RESULT:
The information gathering techniques tools/procedure were  identified successfully
