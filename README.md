# Project 8 - Pentesting Live Targets

Time spent: 1 hours spent in total

> Objective: Identify vulnerabilities in three different versions of the Globitek website: blue, green, and red.

The six possible exploits are:

* Username Enumeration
* Insecure Direct Object Reference (IDOR)
* SQL Injection (SQLi)
* Cross-Site Scripting (XSS)
* Cross-Site Request Forgery (CSRF)
* Session Hijacking/Fixation

Each color is vulnerable to only 2 of the 6 possible exploits. First discover which color has the specific vulnerability, then write a short description of how to exploit it, and finally demonstrate it using screenshots compiled into a GIF.

## Blue

Vulnerability #1: SQL Injection

Description: In the Find a Salesperson category if we use an SQL injection query, we get a message that the Database Query has failed. Thus, we get to know that the inputs are not being properly sanitizes in the blue link.

“blue-vuln1.gif":
 


## Green

Vulnerability #1: Cross-Site Scripting

Description: When we put in feedback from the user’s side and try to look that feedback from the admin’s end a dialogue box pops up indicating that the site vulnerable to a stored XSS attack.

"green-vuln1.gif": 



## Red

Vulnerability #1: Insecure Direct Object Reference

Description: The http link for the Find a Salesperson page has an IDOR vulnerability. The moment we cross a specific number of id’s in the http link it starts showing sensitive information, for instance, who was fired etc.

"red-vuln1.gif":
 



## Notes

Describe any challenges encountered while doing the work

