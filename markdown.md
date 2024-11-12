Security701 Unit 2.4
In unit 2.4 There are 7 sections
- Malware Attacks
- Physical Attacks
- Network Attacks
- Appplication Attacks
- Cryptographic Attacks 
- Password Attacks 
- Indicators 

________________________________________________________________________________________________________________________________________________________________________________________

Malware Attacks

Malware Attacks terms
(1.Malware (2.ransomware (3.Virus (4.Worm (5.Spyware (6.Bloatware (7.Keylogger (8.Logic Bomb (9.Rootkit (10.Trojan

(1. Malware 
- malicious software
types of malware and methods 
- viruses, worms, ransomware, trojan horse, rootkit, keylogger, spyware, bloatware, logic bomb
how you might get malware
- A worm takes advantage of a vulnerability
- Installs malware that includes a remote access backdoor
- Bot may be installed later
- Email link
- Web page pop-up
- Drive-by download

(2. Ransomware
- Software that encrypts programs and data until a ransom is paid to remove it.
protecting vs ransomware
- always have backup, keep OS/apps updated, keep antivirus/antimalware signatures up to date

(3. Virus
- malware that can reproduce itself
- needs you to execute
- reproduces through file systems or network
- may or may not cause problems
- anti-virus very common
virus types
- program viruses (part of app)
- Boot sector Viruses run as the system boots up
- Script viruses OS and many other software run scripts = malicious scripts
- mirco viruses (common in Microsoft office)
- fileless virus (a stealthy virus that opeates through memory

(4. Worm
- malware that self replicates
- doesnt need you to do anything
- uses the network to spread
- can spread really quick
- firewalls and IDS/IPS can mitigate worm infestations (although it is not helpful once worm is inside)

(5. Spyware
- ID theft, affiliate fraud, ads
- browser monitoring
- keyloggers
- usually in an attempt to trick you into installing something malicious
protecting against spyware
- maintain antivirus/antimalware
- always know what you're installing
- consistent backups
- run scans w/ 3rd party software

(6. Bloatware
- unwanted and potentially harmful software preloaded onto new devices.
- can open your system to exploits
- takes up storage/resources
- system may be slower than expected
removing bloatware
- identify and remove manually (easier said than done)
- use built in uninstaller on system using the app's own uninstallers
- 3rd party uninstallers
- always have backups

(7. Keylogger
- malware that tracks your keyboard inputs then sends the data to people with malicious intent
- circumvents encryption protections
types of keylogging
- screen logging
- instant messaging
- clipboard logging

(8. Logic Bomb
- waits for a predefined event
- time bomb (triggered by time or date)
- user event (triggered by user action)
- logic bombs are usually difficult to identify

(9. Rootkit
- originally a unix technique
- malware that modifies core system files
- part of kernel
- can be invisible to the OS
- is invisible to traditional antivirus utilities
finding and removin rootkits
- antimalware scans
-  use a remover specific to the rootkit
- usually made after its discovered
- secure boot with UEFI
- security in the BIOS
- checks to OS signature and confirm nothing has changed before booting

(10. Trojan 
- a type of malware that disguises itself as a legitimate program to gain access to a user's device

___________________________________________________________________________________________________________________________________________________________________________________________

Physical Attacks

Physical Attacks terms
(1.Brute Force (2.RFID Cloning (3. Environmental 

(1. Brute Force
- a brute force physical attack

(2. RFID cloning
- duplicating RFID on access badges, key fobs, etc
- takes seconds
- read one card then copying its data to another

(3. environmental attack
attack stuff supporting the technology
- HVAC
- power
- fire suppression system

__________________________________________________________________________________________________________________________________________________________________________________________

Network Attacks

Network Attacks Terms
(1.Distributed denial of service (2.Amplified (3.Reflected (4.Domain Name System (5.Wireless (6.On-Path (7.Credential replay (8.Malicious code

(1.Distributed Denial of Service (DDoS)
- a malicious attempt to disrupt the normal traffic of a targeted server, service or network by overwhelming the target or its surrounding infrastructure with a flood of Internet traffic.

(2. Amplified (DDos Attack)
- a type of cyberattack in which the attacker sends out a large request, such as to a DNS server or ICMP ping, and receives an extremely large response back.

(3. Reflected (XXS Attack)
-  involves a vulnerable website accepting data (i.e. malicious script) sent by the target's own web browser to attack the target with

(4. Domain Name System (DNS)
- a fundamental part of the internet that translates human-readable domain names into numerical IP addresses

(5. Wireless Deauthentication
- a significant wireless DoS attack that suddenly disconnects people off of wifi

(6. On Path Network Attack and Browser Attack
Network Attack
- redirects your traffic and passes it on to the destination
Browser Attack
- malware/trojan does the proxy work and is able to redirect traffic before and after it is sent to the network
- aka man-in-the-browser
- huge advantage
- even if network traffic was encrypted, attacker still sees it
- everything looks normal to victim

(7. Credential Replay Attack
- A type of network attack where an attacker captures network traffic and stores it for retransmission at a later time to gain unauthorized access to a network
- need access to raw network data
- avoided using encryption or salting of the password

(8. Malicious Code
different types
-executable, scripts, macro viruses, worms, trojan horse, etc

__________________________________________________________________________________________________________________________________________________________________________________________________

Application Attacks

Application Attacks Terms 
(1.Injection (2.Bufffer Overflow (3.Replay (4.Privilege escalation (5.Forgery (6.Directory Travel 

(1. Injection Attacks
- adding your own info into a data stream
 different injectable data types
- HTML, SQL, XML, LDAP, and more

(2. Buffer Overflow
- A buffer overflow is where an attacker will input more information into a buffer than the buffer can hold. 

(3. Replay 
- Using information captured and duplicated at a point in time to then “Replay” that to use at a later date, in turn allowing access to the application and the user privileges of the user you have attacked.

(4. privilege escalation
- Privilege escalation is where an attacker exploits a vulnerability to grant them higher, or ideally administrator privilege on a system.

(5. Forgery = CSRF (Sea Surf, XSRF)
- 1 click attack, session riding 
- CSRF — Cross Site Request Forgery. CSRF tricks a web browser into executing an unwanted action in an application to which a user is logged in.
- website trusts your browser
- requests are made without your consent or knowledge

(6. Directory Traversal or Path Traversal
- Directory traversal is where an attacker gains access to directories that they should not be allowed access to, by utilizing a vulnerability within the server, or within an application.
-Users shouldn't be able to browse the Windows folder

_________________________________________________________________________________________________________________________________________________________________________________________________________

Cryptographic Attacks

Cryptographic Attacks terms 
(1.Downgrade (2.Collision (3.Birthday

(1. Downgrade Attack 
- A type of attack that forces a system to downgrade its security/encryption. The attacker then exploits the lesser security control.


(2. Hash Collision
- Occurs when the hashing algorithm creates the same hash from different texts

(3. Birthday Attack 
- finding a hash collision using brute force
- protect yourself with large has output sizes

____________________________________________________________________________________________________________________________________________________________________________________________

Password Attacks 

Password Attacks Terms
(1.Spraying (2. Brute Force 

(1. Spraying Attack 
- attack an account by trying to login with the top 3 or 4 most common passwords
- if it doesnt work move on

(2. Brute Force Attack 
- trying every password combination until hash is matched
- can take time
- usually done offline
- strong hashing algo slows things down

____________________________________________________________________________________________________________________________________________________________________________________________

# Indicators

Indicators Terms
(1.Account Lockout (2.Concurrent Session Usage (3.Blocked Content (4.Impossible Travel (5.Resource Consumption (6.Resource Inaccessibility (7.Out-of-cycle Logging (8.Published/Documented Info (9.Missing Logs

(1. Account Lockout
- exceeded login attempts
- can be disabled by an administrator
- attacker may plan to lock your acc and call help desk impersonating you to reset password

(2. Concurrent Session Usage
- multiple acc logins from multiple locations
- can be hard to track down

(3. Blocked Content
- attacker wants to stay as long as possible
- blocks security patches, updates, removal tools, etc

(4. Impossible Travel
- impossible travel in authentication logs can be a sign of intrusion

(5. Resource Consumption
- if resource consumption spikes at unusual times or is higher than usual
- firewall logs show the outgoing transfer
- IP addresses, timeframes

(6. Resource Inaccessibility
- server is down, not responding, or is having a network disruption

(7. Out-of-cycle Logging
- logs that occur at an unexpected time

(8. Published/Documented Info
- This is when documentation has been made publicly avaliable that shouldnt have been.

(9. Missing Logs
- log info is evidence attackers delete logs to cover tracks
- logs may be incriminating, missing logs are suspicious, logs should be secured and monitored
