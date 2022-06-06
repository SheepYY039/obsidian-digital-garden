---
{"dg-publish":true,"permalink":"/62-encyclopedic/62-01-security-plus/20220606142437-malicious-scripts/","dgHomeLink":true,"dgPassFrontmatter":false}
---


# Malicious Scripts

## PowerShell

- A command line for system administrators 
	- `.ps1` file extension 
	- Included with `Windows 8/8.1, 10` 
- Extends the functionality of a "Normal Windows Command Line"
	- Able to manage almost all aspects of the Windows OS 
	- Uses `cmdlets` (`command-lets`) 
	- PowerShell Scripts and Functions 
	- Standalone executables 
- If attackers want to attack the Windows OS 
	- PowerShell is the best starting point 
	- Attackers will be able to 
		- System administration 
		- Active domain administration 
		- File share access 

## Python

- General-purpose scripting language 
	- `.py` script extension 
- Popular in many technologies 
	- Broad appeal and support 
	- Can be used in all OS 
- Commonly used for cloud orchestration 
	- Create and tear down application instances 
- Great for attacking cloud-based infrastructure 
	- Routers 
	- Servers 
	- Switches 

## Shell Script

- Scripting in the `Unix` / `Linux` Shell 
	- Automate and extend the command line 
	- `Bash`, `Bourne`, `Korn`, `C`
- Starts with a `shebang` or `hash-bang` (`#!`) 
	- Often has a `.sh` file extension 
- Useful when 
	- Attacker using a linux/Unix environment 
	- Trying to attack a Unix/Linux environment 
- Good for 
	- Web 
	- Database 
	- Virtualization servers 
- Control the OS from the command line 
	- [[62-Encyclopedic/20220516095203-malware|Malware]] has a lot of options 

## Macros

- Automate functions within an application or OS 
- Designed to make the application easier to use 
	- But can often create security vulnerabilities 
- Attackers create automated exploits 
	- They just need the user to open the file 
	- Prompts to run the macro 

## Visual Basic for Applications (VBA)

- Automates processes within Windows applications 
	- Common in Microsoft Office 
- A powerful programming language 
	- Can interact with office applications and also the OS 

> [!example] VBA Vulnerability 
> **CVE-2010-0815**/ **MS10-031**
> - VBA does not properly search for ActiveX controls in a document 
> - allows attackers to run arbitrary code embedded in a document 
> - Easy to infect a computer 
