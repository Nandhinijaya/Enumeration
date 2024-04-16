# Enumeration
Enumeration Techniques

# Explore Google hacking and enumeration 

# AIM:

To use Google for gathering information and perform enumeration of targets

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various Google hacking keywords and enumeration tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified:
Information Gathering.

Google Hacking:

Google hacking, also known as Google dorking, is a technique that involves using advanced operators to perform targeted searches on Google. These operators can be used to search for specific types of information, such as sensitive data that may have been inadvertently exposed on the web. Here are some advanced operators that can be used for Google hacking:

## site: 
This operator allows you to search for pages that are within a specific website or domain. For example, "site:example.com" would search for pages that are on the example.com domain.
Following searches for all the sites that is in the domain yahoo.com
## output:
![a](https://github.com/Nandhinijaya/Enumeration/assets/121998147/0a3d98c0-55f7-4463-ab2d-4906e8c245fb)


## filetype:
This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files.
Following searches for pdf file in the domain yahoo.com
## output:
![b](https://github.com/Nandhinijaya/Enumeration/assets/121998147/95580224-dbd2-4742-944d-417a000efb08)


## intext: 
This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.
## output:
![c](https://github.com/Nandhinijaya/Enumeration/assets/121998147/089ad72d-0384-4372-a73c-870012ec6afd)


## inurl: 
This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.
## output:
![d](https://github.com/Nandhinijaya/Enumeration/assets/121998147/6c074d0c-6ae7-4fe0-8206-a0e1cb2f96bc)


## intitle: 
This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag.
## output:
![e](https://github.com/Nandhinijaya/Enumeration/assets/121998147/e581bbde-8331-4a20-b042-50117267e8b6)


## link: 
This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.
## output:
![f](https://github.com/Nandhinijaya/Enumeration/assets/121998147/69f30056-a212-4afb-b194-05a74fda0fd1)

## cache:
This operator allows you to view the cached version of a page. For example, "cache:example.com" would show the cached version of the example.com website.
## output:
![g](https://github.com/Nandhinijaya/Enumeration/assets/121998147/2fb62b35-929d-4863-9c9b-c96350a76185)

 
# DNS Enumeration
## DNS Recon
provides the ability to perform:
Check all NS records for zone transfers
Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT)
Perform common SRV Record Enumeration
Top level domain expansion
## OUTPUT:
![1](https://github.com/Nandhinijaya/Enumeration/assets/121998147/b61db213-21b5-458e-a469-14650ae85dbe)






## dnsenum
Dnsenum is a multithreaded perl script to enumerate DNS information of a domain and to discover non-contiguous ip blocks. The main purpose of Dnsenum is to gather as much information as possible about a domain. The program currently performs the following operations:

Get the host’s addresses (A record).
Get the namservers (threaded).
Get the MX record (threaded).
Perform axfr queries on nameservers and get BIND versions(threaded).
Get extra names and subdomains via google scraping (google query = “allinurl: -www site:domain”).
Brute force subdomains from file, can also perform recursion on subdomain that have NS records (all threaded).
Calculate C class domain network ranges and perform whois queries on them (threaded).
Perform reverse lookups on netranges (C class or/and whois netranges) (threaded).
Write to domain_ips.txt file ip-blocks.
This program is useful for pentesters, ethical hackers and forensics experts. It also can be used for security tests.
## output:
![2](https://github.com/Nandhinijaya/Enumeration/assets/121998147/9c1b5597-d4b3-47db-aa41-b9222044cf0e)
![3](https://github.com/Nandhinijaya/Enumeration/assets/121998147/de0fb000-3bd4-47ea-b37b-a292b2bc34a7)

## smtp-user-enum
Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO.

In metasploit list all the usernames using head /etc/passwd or cat /etc/passwd:

select any username in the first column of the above file and check the same
![4](https://github.com/Nandhinijaya/Enumeration/assets/121998147/84a76fbf-953e-4ffc-b2ba-dd995737b2ea)


# Telnet for smtp enumeration
Telnet allows to connect to remote host based on the port no. For smtp port no is 25
telnet <host address> 25 to connect
and issue appropriate commands
  
 ## Output
  ![te](https://github.com/Nandhinijaya/Enumeration/assets/121998147/ed9d40e6-a1be-4026-8b58-40b224d7fc90)

  

## nmap –script smtp-enum-users.nse <hostname>

The smtp-enum-users.nse script attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands. The goal of this script is to discover all the user accounts in the remote system.


## OUTPUT:

![5](https://github.com/Nandhinijaya/Enumeration/assets/121998147/78eb3ba3-f5ef-4a17-8e46-a89c9212ee27)

## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully

