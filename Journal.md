# Cybersecurity Learning Journal

A record of hands-on security labs, technical observations, experiments and learning progress.

---

## Git & GitHub Workflow

- Reconnected my local environment to my existing GitHub repository.
- Practiced cloning, checking repository status and reviewing commit history.
- Used Git to maintain a record of my cybersecurity learning.

---

## Web Application Security

### SQL Injection (SQLi)

**Platform:** SQLi-Labs, PortSwigger Web Security Academy

**Topics explored:**
- SQL query structure and injection contexts.
- UNION-based SQL injection.
- Column count identification.
- Database, table and column enumeration.
- Filter and blacklist bypasses.
- Error-based SQL injection exploration.
- Blind SQL injection.
- Cookie-based SQL injection.
- SQLmap and manual testing.
- Injection into queries with different structures.

**Lab progress:**
- SQLi-Labs: progressed through Less-57.
- PortSwigger: explored SQL injection and blind SQL injection labs.

**Technical record:**

#### SQLi-Labs Less-27

- Investigated a case-sensitive blacklist.
- Explored mixed-case keyword bypasses.
- Used alternative whitespace representation.
- Examined UNION-based injection.
- Identified the number of columns.
- Explored database metadata.

**Main lesson:** Understand the query context, filtering behavior and database structure rather than memorizing payloads.
**Status:** Practiced; requires continued revision.
### Cross-Site Scripting (XSS)

**Platform:** XSS Game and Web Security Academy
- Stored XSS.
- DOM-based XSS.
- Filter and validation behavior.
- Attempted an intermediate/advanced source-to-sink assessment.
- Scored 3/8 on the assessment.
**Status:** Practiced; requires revision and further assessment.

---

### Cross-Site Request Forgery (CSRF)

**Environment:** Local PHP lab and PortSwigger Web Security Academy

**Topics explored:**
- Session-based authentication.
- Cookies and authenticated requests.
- CSRF tokens.
- Missing and invalid token behavior.
- HTTP request modification.
- POST and GET behavior.
- Method-dependent behavior.
- SameSite, HttpOnly and Secure cookie attributes.

**Practice:**
- Built a local PHP CSRF demonstration.
- Tested authenticated request behavior.
- Investigated token validation.
- Modified requests using Burp Suite.
- Explored CSRF lab scenarios.

**Main lesson:** Authentication does not automatically protect an application from unauthorized actions initiated through a victim's browser.

**Status:** Practiced; requires continued revision and testing.

---

### Command Injection (CMDi)

**Platform:** Pwn.college

**Topics currently exploring:**
- Web applications interacting with the operating system.
- Linux command execution.
- Challenge source-code inspection.
- HTTP requests using curl.
- GET and POST request construction.
- URL encoding.
- Injection contexts and query structure.

**Main lesson:** Understand how user-controlled input reaches an external command or execution context.

**Status:** Exploratory.

---

## Networking & Linux Fundamentals

**Topics studied or explored:**
- Linux command-line basics.
- HTTP fundamentals.
- TCP and UDP.
- OSI model.
- Nmap.
- Wireshark.
- HTTP headers and request analysis.

**Status:** Studied; practical revision ongoing.

---

## Tools & Environment

- Kali Linux
- Burp Suite
- Nmap
- Wireshark
- SQLmap
- Linux CLI
- Git & GitHub
- PHP
- MySQL
- JavaScript
- Bash

---

## Learning Direction

My current direction is Web Application Security, focusing on understanding vulnerabilities, analyzing requests and application behavior, practicing in authorized labs and gradually expanding toward vulnerability research and low-level security.
**Main lesson:** Identifying the source, understanding the sink and analyzing the execution context are essential to DOM XSS analysis.


**Practice:**
- Completed all 6 XSS Game DOM XSS levels.
- JavaScript execution contexts.
- Source-to-sink analysis.
- HTML and JavaScript injection contexts.



