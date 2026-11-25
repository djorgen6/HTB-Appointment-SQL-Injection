# Hack The Box – Appointment

A Hack The Box Starting Point Tier 1 lab focused on network enumeration, SQL Injection, and web application authentication bypass.

## Project Scope

Completed a beginner-level penetration testing exercise using Kali Linux to identify and exploit a SQL Injection vulnerability in a web application's login page.

The objective was to enumerate the target, examine its web directories, identify the vulnerability, and gain access to the application without valid login credentials.

## Tools Used

- **Kali Linux** – Penetration testing environment.
- **Nmap** – Network scanning and service enumeration.
- **Gobuster** – Web directory enumeration.
- **Apache HTTP Server** – Identified as the target's web server.
- **Web Browser** – Accessing and testing the target application.
- **Hack The Box VPN** – Connecting to the lab environment.

## Results & Key Takeaways

- Successfully identified the target's open HTTP port (80) and Apache web server.
- Used Gobuster to enumerate web directories and resources.
- Discovered an SQL Injection vulnerability in the login form.
- Exploited the vulnerability to bypass authentication and gain access.
- Learned how SQL Injection can compromise web application authentication and why input validation and parameterized queries are important security practices.

## Final Thoughts
This lab was insightful and taught me a lot about SQL Injection attacks. Using basic brute-forcing techniques helped me understand the vulnerabilities that can exist when web applications and their credential verification processes are not properly set up and configured.

I also learned about the programming language Golang (Go), which is designed by Google, as well as Gobuster, a tool written in Go that can be used for web directory brute-forcing.

Overall, I learned a great deal about brute-forcing techniques and their potential effectiveness against misconfigured applications. I'm glad I was able to practice some of these techniques myself to gain a better understanding of how they work.

**Platform:** Hack The Box  
**Difficulty:** Very Easy  
**Category:** Starting Point Tier 1

**Lab Link:** [Appointment – Hack The Box](https://www.hackthebox.com/machines/appointment)
