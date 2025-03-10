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
Tested By: Rohith v
Register no.: 212223040174
```
## OUTPUT:

![img1](https://github.com/user-attachments/assets/1c8c253e-ce6d-45a2-8157-77c490fb7c54)

## Finding IP address:

ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.

```ping saveetha.ac.in```

## output:

![img2](https://github.com/user-attachments/assets/5ceadf17-9b92-4fd4-8b5b-20c61c3d4085)

## Finding Hosting Company:

get further detail by using ip2location.com website.

## output:

![img3](https://github.com/user-attachments/assets/dab37759-b616-4a3a-af98-a1f33707aa0f)

## History of the website:

## Output:

![img4](https://github.com/user-attachments/assets/61d09b80-0dea-4ed1-8f8b-6fdaff54df61)

## Webserver Fingerprinting:

## Netcat:

```nc 172.17.52.118 80```

## OUTPUT:

![img5](https://github.com/user-attachments/assets/fa608c35-102c-4c30-958a-49dc8416dd23)

## nmap:

```nmap -p 21 -sV --script=banner ftp.vim.org```

## OUTPUT:

![img6](https://github.com/user-attachments/assets/6e96994f-a241-451a-b4b9-061b115eb997)

## Whatweb:

```whatweb infosys.com```

```whatweb zoho.com```

```whatweb -v -a 3 172.17.52.201```

## OUTPUT:

![img7](https://github.com/user-attachments/assets/b60dcfe6-9c94-4953-81cb-8ea056f8bf3b)

## httprint:

```httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more```

## OUTPUT:

![img8](https://github.com/user-attachments/assets/3c0ca970-f2de-4d3b-b3a2-c19026b7416c)

## Tracing the Location

## TCP Traceroute:

```sudo traceroute -T www.saveetha.ac.in```

## OUTPUT:

![imh9](https://github.com/user-attachments/assets/e4e72beb-1417-4c18-b03b-0d0f46f27281)

## UDP Traceroute:

```sudo traceroute -U www.saveetha.ac.in```

## OUTPUT:

![img10](https://github.com/user-attachments/assets/c50a4276-cd64-40d5-a404-d68a9121f598)

## ICMP Traceroute:

```sudo traceroute  www.saveetha.ac.in```

## OUTPUT:

![img11](https://github.com/user-attachments/assets/500208a1-6ee9-45c6-809c-d301a17d2940)

## RESULT:

The information gathering techniques tools/procedure were  identified successfully
