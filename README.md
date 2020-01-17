# Application-Security

Data validation
  -input validation
    -prepared statement, pdo(bind)
    -limit char
    -htmlspecialchars
    -extension type, limit size
Authentication
Session management
Authorization
Cryptography
Error handling
Logging

Methodology
-Use tools
-Manual, follow top10 OWASP

SQLi
-impact
  -dump db, modify db
  -server side vuln = sql

XSS
-impact
  -steal session, deface, redirect
  -client side vuln = html
-mitigation
  -htmlspecialchars, htmlentities
  #htmlentities effect performance(if,else)
  
Unrestricted file upload
-impact
  -attack backend client side, backdoor
  
OS Command Injection
-mitigation
  -can enable or disable, if really need, whitelist what command
-in Java = runtime, processbuilder
-in php = exec_md()

SAST VS DAST
-dast effect infra
-complement each other

IAST
-interactive

WAF = AI
RIPS - PHP Security Analysis
XAMPP - Web server
DVWA - Master app

IOS Directory
/var/containers/Bundle/Application/xxx/xxx.app
zip -r xx.ipa Foldername

/var/mobile/Containers/Data/Application/
/var/mobile/Containers/Shared/AppGroup


