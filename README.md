# CodePath-Week-8-Project
# Project 8 - Pentesting Live Targets

Time spent: 5 hours spent in total

> Objective: Identify vulnerabilities in three different versions of the Globitek website: blue, green, and red.

The six possible exploits are:
* Username Enumeration
* Insecure Direct Object Reference (IDOR)
* SQL Injection (SQLi)
* Cross-Site Scripting (XSS)
* Cross-Site Request Forgery (CSRF)
* Session Hijacking/Fixation

Each version of the site has been given two of the six vulnerabilities. (In other words, all six of the exploits should be assignable to one of the sites.)

## Blue

Vulnerability #1: SQL Injection
GIF Walkthrough: ![alt text](https://github.com/davjd/CodePath-Week-8-Project/blob/master/sqlWorking.gif)

Vulnerability #2: Session Hijacking/Fixation
GIF Walkthrough: ![alt text](https://github.com/davjd/CodePath-Week-8-Project/blob/master/blue2.gif)


## Green

Vulnerability #1: Cross-Site Scripting
https://github.com/davjd/CodePath-Week-8-Project/blob/master/xssGreen.gif

Vulnerability #2: Username Enumeration
https://github.com/davjd/CodePath-Week-8-Project/blob/master/enum.gif

## Red

Vulnerability #1: Insecure Direct Object Reference
https://github.com/davjd/CodePath-Week-8-Project/blob/master/red1.gif

Vulnerability #2: Cross-Site Request Forgery
https://github.com/davjd/CodePath-Week-8-Project/blob/master/red2.gif


## Notes

This lab was probably the most challenging so far. Finding which site had which vulnerability took what felt like hours. Fortunately, the descriptions has some hints which helped. The last vulnerability was crazy hard. I had to ask for help for it. But I was able to get it. :)
