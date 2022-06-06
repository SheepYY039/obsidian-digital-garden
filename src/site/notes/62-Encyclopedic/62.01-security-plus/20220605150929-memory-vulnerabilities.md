---
{"dg-publish":true,"permalink":"/62-encyclopedic/62-01-security-plus/20220605150929-memory-vulnerabilities/","dgHomeLink":true,"dgPassFrontmatter":false}
---


# Memory Vulnerabilities

>[!word] Memory Vulnerabilities #vulnerability 
> Manipulating memory can be advantageous
> - Relatively #difficult to accomplish 

## Cause of Memory Vulnerabilities

#cause 

### Memory Leak

A great choice for creating a [[62-Encyclopedic/62.01-security-plus/20220606122813-denial-of-service|DoS]] 

- Unused memory is not properly released 
- Begins to slowly grow in size 
- Eventually uses all available memory 
- System crashes or Application failing 

### NULL Pointer Dereference

- When an attacker can make a program point to a NULL memory where nothing exists
- Then application crashes, debug information is displayed, and [[62-Encyclopedic/62.01-security-plus/20220606122813-denial-of-service|DoS]]

### Integer Overflow

- When a large number is placed into a small section of memory 
	- The extra space has to go somewhere 
	- Which usually goes to the part of memory that is overflowed 
- You shouldn't be able to manipulate memory this way 
- #difficult to find 
	- in which this behaviour is repeatable
	- But if they do
		- can duplicate 
		- can manipulate in a way that is advantageous to them in controlling the system 
	- Then it is a very powerful attack 
