# Course Overview 
Introductory to computer security. Covers security issues in software design and development from technical, social and legal viewpoints. Topics include cryptography, security models, software security, authentication, authorization, and system security.

**Course Time:**	Tuesday, Thursday 3:05pm-4:20pm

**Course Location:**	EPS 108	

**Course Instructor:**	Eric Fulton. 

**Office Hours:**	Thursday immediate after class until 5pm

**Prerequisites:**	CSCI 232

**Number of credits:**	3

**Required Textbook:**	None

## Goals
The overarching goals fo the class are:

1. Understand the many different aspects of information security.
1. Develop Skills for: researching security issues, learning new tools, developing new tools, and more.
1. Practice offensive security techniques.
1. Acquire basic knowledge of various information security topics.  
1. Question and evaluate information presented 

By the end of the class, you will have acquited the following skills: 

1. Perform a penetration test from beginning to end
1. Discuss and describe basic hacking techniques
1. Identify and recongnize exploitable situations and logically attempt to exploit flaws
1. Write a report based on penetration testing findings suitable for a C-Level executive
1. Formulate and execute an independent project to assist in automated testing
1. Present orally the results of an independent project
1. Translate and restate results presented in peer-reviewed journals (or hacking zines)


## Topics to be covered
* Hacking
	* Trust, Security Domains, Common Attacks
	* Information Gathering
	* Vulnerability Analysis and Scanning
	* Exploitation
	* Post-Exploitation and Persistence
* Applied cryptography
	* Goals of Crypto
	* Stream Cyphers
	* Block Cyphers
	* Asymmetric Crypto
	* Authentication/Integrity
* Hacker Culture
* Reverse Engineering
* Web Application Security
	* OWASP Top 10
* System Security
	* Control Flow Hijacking
	* Execution Safefy
	* Information Flow
	* Common Defenses
	* Security Architectures
	* Exploitation
* Network Security
	* Scanning, firewalls, and vulnerability scanning 
	* Denial of Service
	* Intrusion Detection
	* Network analysis

# Grading and Policies
## Grading
The following grade scale will be used, after any curving takes place, based on class average as follows:

Percentage | Grade
--- | ---
89.5 - 100: | A
79.5 - 89.4: | B
69.5 - 79.4: | C
59.5 - 69.4: | D
< 59.5: | F

## Graded Items

Item | Percentage of Grade
--- | ---
Practicum 1 | %15
Practicum 2 | %15
Practicum 3 | %20
Assignments | %50 (5 percent each)

Late homework is not accepted as staff cannot hand out solutions or graded assignments until everyone has turned in their work.  Only in emergency or exceptional circumstances, such as a funeral or hospitalization, is late work accepted.  Personal scheduling issues like interviews, technology problems, etc. are not allowed as homework can be performed on any computer and can be submitted remotely.  

## Homework Style Guide
All written homework assignments are to be written in the [Markdown Syntax](https://help.github.com/articles/github-flavored-markdown/) unless otherwise stated.  

## Policies

All students should read the MSU Student Conduct Code.  

Due to the nature of this class and the skills being taught an additional ethics document will need to be signed and returned at the beginning of the second class for a student to continue enrollment in CSCI 491.  Unethical behaviour including cheating, plagiarism, unlawful access of computer systems, et al. will immediately result in a class failure and the incident will be reported to the Dean of Students.  

When it comes to homework assignments, you _MAY_:

* Work with other people on your team if allowed. 
* Share ideas with people in other teams
* Help other teams troubleshoot problems.
* Use the power of the Internet

You _MAY NOT_:

* Share code you write with other teams
* Submit code that someone on your team did not write.
* Modify another teams solution or code found online and claim it as your own.

Failure to abide by these rules will result in at "F" for the course and being reported to the Dean of Students.  Please ask if you have any questions regarding your actions. In particular:

* Don't break University rules or laws. Examples of prohibited activities include network scanning, network exploitation, "testing" the security of a system without explicit permission from all necessary parties, etc.
* Don't attempt to hack the University.  You won't realize you're being watched until you're being sent to jail.

# General Course Knowledge Requirements
There are some basic competencies necessary to be successful in this course.  By no means must you be an expert in the following topics, but it would be useful to have a general familiarity.  A weekend review of the following topics will give you the basic tools to necessary to succeed.  

## Basic Computer Systems

* [Simple CPU](http://www.simplecpu.com/Binary.html)

## *Nix Knowledge
Linux is the most typically used *nix operating system in use today and will be the foundational tool for CSCI 476.  A familiarity with the Bash shell and Linux utilities can be gained from the following resources:

* [Linux Command](http://linuxcommand.org/index.php)
* [Linux Tutorial](http://ryanstutorials.net/linuxtutorial/)
* [Bash by Example](http://www.ibm.com/developerworks/linux/library/l-bash/index.html)
* [Shell-Fu](http://www.shell-fu.org/lister.php?top)
* [Explain Shell](http://explainshell.com/)
* [Kali Tools](http://tools.kali.org/tools-listing)

## Networking Knowledge

* [TCP/IP Illustrated](http://en.wikipedia.org/wiki/TCP/IP_Illustrated)
* [IP Addressing and Subnetting for New Users](http://www.cisco.com/c/en/us/support/docs/ip/routing-information-protocol-rip/13788-3.html)
	
## Scripting Competency

* [Bash](http://tldp.org/LDP/abs/html/)
* [Ruby](http://www.codecademy.com/en/tracks/ruby)
* [Python](http://www.codecademy.com/en/tracks/python)

## Hardware and software requirements
Your primary platform will be [Kali Linux](http://www.kali.org/downloads/).  You can use Kali as a native installation, in a virtual machine, or on a bootable usb.  If you are using a bootable usb ensure that you use it in persistence mode to ensure OS continuity.

# Schedule 
Guest Speakers will be announced during the term and dates may change.  

Date | Topic | Graded Events | Extra Reading
--- | --- | --- | ---
1.15.15 | Course Introduction | Ethics Form |  
1.20.15 | Trust, Security Domains, Common Attacks |  Assignment 1 |  
1.22.15 | Information Gathering |   | 
1.27.15 | Vulnerability Analysis and Scanning |   |  
1.29.15 | Exploitation |  Assignment 2 |  
2.3.15 | Post Exploitation, Persistence | | 
2.5.15 |  |  Practicum 1 |  
2.10.15 | Intro to Cryptosystems | |
2.12.15 | CypherPunks and Hacker Culture |  Assignment 3 |  
2.17.15 | Weaponized Scripting - Python | | 
2.19.15 | Weaponized Scripting - Powershell |  Assig
nment 4 |  
2.24.15 | Intro to Reverse Engineering | |
2.26.15 | Olly, Ida, and Immunity |  Assignment 5 |  
3.3.15 | Practice questions and Review | |
3.5.15 |   |  Practicum 2 |  
3.10.15 | **Spring Break**
3.12.15 | **Spring Break**
3.17.15 | Report Writing | |
3.19.15 | Web Application Security Overview & Guest Speaker |  |
3.24.15 | Web Applications - Vulnerability Scanning | | 
3.26.15 | Web Applications - Exploitation |  Assignment 6 |  
3.31.15 | Understanding the Network
4.2.15 | Network - Attacks |  Assignment 7 |  
4.7.15 | Network - Defenders View
4.9.15 | Network - File Carving |  Assignment 8 |  
4.14.15 | Computer Forensics 
4.16.15 | Forensics - Acquisition and Analysis |  Assignment 9 |  
4.21.15 | Forensics - Network 
4.23.15 | Catpure the Flag |  Assignment 10 |  
4.28.15 | Review
4.30.15 | Practice Practicum
5.4.15 | **Finals Week** |  Practicum 3 |  
5.8.15 | **Spring Semester Ends**

CC-BY-NC-SA: Attribution Noncommercial Share Alike

