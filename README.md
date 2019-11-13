# Web Security Testing
Intro to Web Security Testing - .Net Core, NodeJS (Express), php


## Tools
- Rudimentory Hacking
  - Use Google (yes Google) ! = 
    - Search Syntax: https://ahrefs.com/blog/google-advanced-search-operators/
    - more examples: https://books.google.com/books?id=bvB1-MmhEjQC&pg=PA140&lpg=PA140&dq=intext:+error+sql&source=bl&ots=emvq4xWhp5&sig=ACfU3U2qBKM-aDHUSHMDcJVxyU1p5IE6uw&hl=en&sa=X&ved=2ahUKEwjctKPDhejlAhUQnawKHaZED-cQ6AEwDHoECAkQAg#v=onepage&q=intext%3A%20error%20sql&f=false
- Large list of Tools (https://hackertarget.com/10-open-source-security-tools/) 
- Burp Suite (Market Leader)
  1. https://portswigger.net/burp (Download the Community Edition)
- XssPy - Python (https://github.com/faizann24/XssPy) 
  1. Clone the PHP Script
  2. Run: 
    pip install mechanize
  3. Check Headers for Details (HTTP Response Headers)
    python .\XssPy.py -u rocketpost.io
- Grabber (http://rgaucher.info/beta/grabber/)
  1. pip install beautifulsoup4
  2. download PyXML
    2.a. gzip -dc PyXML-0.8.4.tar.gz | tar -xvf -
  3. 
 
## Fundamentals
OWASP - Open Web Application Security Project (OWASP) [https://www.owasp.org/index.php/Main_Page]
# Common Attacks
  - Stored Cross-site Scripting (XSS).
  - SQL Injection.
    * Cheat Sheet (https://www.netsparker.com/blog/web-security/sql-injection-cheat-sheet/)
  - Authentication bypass.
  - Directory traversal abuse.
  - Unrestricted file upload.
