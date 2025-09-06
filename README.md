# InjecTrak
InjecTrak is a project where on the cyber side, runs many different tests, to see how vulnerable a website can be at glance. This would then be put into a report format for the user to read. On the software side, the goal is to be able to manage data, create a front end, and have a well developed structure for more addons.

Background:

In a world where AI is evolving, the risk of being hacked is becomming more and more common. The solution to the risk of having your information stolen, is by being careful to not get tricked into giving away your information. Back then, it was easy to find fradulent links, but with the growing technology of today's world, it becomes more difficult. InjecTrak's job is to help scan websites vulnerability, to then paint a picture for the user to see "If this site is safe". 


Cyber:

On the cyber side of the project, is where many different vulnerability testing tools come in. This is the list of tools being used here:
 - Port Scanner
 - SSL/TLS Checker
 - HTTP Headers Analyzer
 - SQL Injection Detector
 - XSS (Cross-Site-Scripting) Tester
 - Directory/Path Traversal Scanner
 - CMS & Plugin Detector
 - Sitemap Analyzer
 - Password Strength Checker
 - Content Security Policy Validator

At the end of running all the tools, then there will be a report given on what was the result. It gives a rating as well as some minor then some major comments on why it recieved that rating(if it was a low rating). There will then be an option to export the report to a pdf which would have options like "send to email" where it would send to an email, and more options later on

Software:

On the software side of the project, both backend and frontend would be focused on. On the front end, the goal is to create a user friendly interface. The only input that the program will take from the user is a sign in feature, and also websites that they want scanned. There will also be a list of already tested websites, where there would be a choice. One of the choices would be to scan it again to update the score it would get, and the other choice would be to just check the score. This is to save resources, and time. 
Incorporated in the project, would also show if a website can be tested on or not. Paywalls on websites would not let the program scan the contents because it would be deemed unethical. Instead, the program will return saying that there is a paywall detected, and we cant test that website. 

Notes on Software Side
- From the report on the cyber side of the project, the software has to take account of how the report would work and how it would be outputted
- A scanner will be used to scan the websites (backend)
- A well formed database would be made (backend)

Legality:

Creating a vulnerability tester against websites is actually quite illegal. The tester is bascially a form of hacking the website to see how well it deals with attacks, which in this day in age, not allowed. To combat this, I have decided to create a secure password so only I can run the program. Also, I would be using this program to test against websites that give me full permission to try and find vulnerabilities.
