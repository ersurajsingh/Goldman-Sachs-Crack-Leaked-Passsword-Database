# Goldman Sachs Virtual Engineering Program : Crack Leaked Passsword Database
## Password Controls and Security Policies
### Overview
As a governance analyst it is part of the duty to assess the level of protection offered by implemented controls and minimize the probability of a successful breach. 
Analysts often need to know the techniques used by hackers to circumvent implemented controls and propose uplifts to increase the overall level of security in an organization. 
Gaining valid credentials gives the attackers access to the organization’s IT system, thus circumventing most of perimeter controls in place.

![5b70d4cbfa424a109b65bf870a2b65fa-0001](https://user-images.githubusercontent.com/36544126/129121470-6e9b2e7e-8dbd-4f3a-83f7-d2d407e73fb3.jpg)


## Project Objective
### Tasks Given
To crack as many passwords as possible with available tools (e.g. use Hashcat)and to determine :
- [x] What type of hashing algorithm was used to protect passwords?  
- [x] What level of protection does the mechanism offer for passwords?  
- [x] What controls could be implemented to make cracking much harder for the hacker in the event of a password database leaking again?  
- [x] What can you tell about the organization’s password policy (e.g. password length, key space, etc.)?  
- [x] What would you change in the password policy to make breaking the passwords harder?  

Here is a sample data file containing hashes dumped together:
(https://cdn.theforage.com/vinternships/companyassets/MBA4MnZTNFEoJZGnk/passwd_dump.txt)  

All the passwords which are compromised were using MD5 Message-Digest Algorithm which is a weaker hash algorithm and is prone to collisions and suffer from extensive vulnerabilities 
Using the resources and softwares available like Hashcat , md5decrypt.net , it wasn't much challenging to crack the passwords.
I observed that the organization’s password policy (e.g. password length, key space, etc.) was very weak and not standardized. I would suggest that we use a robust password encryption mechanism in creating hashes for the password based on SHA Hash Function.  
I tried to observe and find a pattern in the passwords being used in the organization which are :  
• Least Size of the password was 6 which is lesser than the normal password size being used by different
online platforms(i.e. 8) and not to mention , length plays a major role in this.  
• There isn't any standard protocol or criteria in passwords being set .  
• There were too many common passwords being used which are easy to guess as well and don't require
any software.  

# Project Report and Observations

I went on to gain a lot of information on the algorithms and I submitted a report as well.  
Here is the Report I submitted.  

(https://docs.google.com/document/d/1CD7yYVrt3Akechy0jnIDAwwF443agIWCdZ0ounJG4uo/edit?usp=sharing)  




