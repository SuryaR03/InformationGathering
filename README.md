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

http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

```
Tested By: SURYA R
Register no.: 212223110056
```
## OUTPUT:
![Screenshot 2025-03-07 133007](https://github.com/user-attachments/assets/964147d2-7eaf-4e21-88b3-2ce57b7a8d09)


## Finding IP address:

ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.

```ping saveetha.ac.in```

## output:

![WhatsApp Image 2025-03-14 at 19 19 22_a0deb5ee](https://github.com/user-attachments/assets/e2126f97-83ba-47de-8440-b01582c951ff)


## Finding Hosting Company:

get further detail by using ip2location.com website.

## output:

![Screenshot 2025-03-07 133338](https://github.com/user-attachments/assets/db6869b1-fcaa-430c-9abb-4e41c49b1b6f)


## History of the website:

## Output:
![Screenshot 2025-03-14 192942](https://github.com/user-attachments/assets/4d3bb96d-e831-4f0f-9b7d-bf4b683998db)


## Webserver Fingerprinting:

## Netcat:

```nc 172.17.52.118 80```

## OUTPUT:

![EH NC](https://github.com/user-attachments/assets/cd96b74a-520e-4615-88dc-46b1f63c6f34)


## nmap:

```nmap -p 21 -sV --script=banner ftp.vim.org```

## OUTPUT:

![EH NMAP](https://github.com/user-attachments/assets/31d2bdec-0367-4d5d-91de-60cd6077a232)


## Whatweb:

```whatweb infosys.com```

```whatweb zoho.com```

```whatweb -v -a 3 172.17.52.201```

## OUTPUT:

![EH WHATWEB](https://github.com/user-attachments/assets/f128617f-7f80-4793-9fd4-297b18b3efad)


## httprint:

```httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more```

## OUTPUT:

![EH HTTPRI](https://github.com/user-attachments/assets/3562176e-fbe9-4e07-8fbf-e459e53e2c0e)


## Tracing the Location

## TCP Traceroute:

```sudo traceroute -T www.saveetha.ac.in```

## OUTPUT:
![TCP](https://github.com/user-attachments/assets/95950f17-5009-4ae5-ab13-3c7b5d7ea723)


## UDP Traceroute:

```sudo traceroute -U www.saveetha.ac.in```

## OUTPUT:

![ICT TRACE](https://github.com/user-attachments/assets/0d19a07e-df3b-4a4b-ab02-208c61a1f4d2)


## ICMP Traceroute:

```sudo traceroute  www.saveetha.ac.in```

## OUTPUT:

![ICMP](https://github.com/user-attachments/assets/8f94883a-13c9-47d5-8177-ff91afe422d0)


## RESULT:

The information gathering techniques tools/procedure were  identified successfully
