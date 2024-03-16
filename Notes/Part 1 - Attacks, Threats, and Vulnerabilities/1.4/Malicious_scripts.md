# Malicious Scripts

Scripting and automation are very effective at performing tasks without the user present. It can also occur quickly and error free; it is as good as the code. Additionally, the attacker can be running many automation scripts in parallel. 

**Windows Powershell**
- command line for system adminstrators 
- **.ps1** file extension
- contains extended command line functions (e.g. cmdlets, powershell scripts, executables etc.)


**Python**
- general purpose scripting language
- broad appeal and support
- popular usage in cloud based environments 
- attack infrastructure (routers, server, switches)

**Shell Script**
- scripting UNIX/Linux shell
- *#!/bin/bash* = shebang opener w/ shell type listed
- *.sh* file extension
- attackers can control the OS from the command line

**Macro**
- automate functions within an application
- simplifies usage but can create security vulnerabilities
- user opens file w/ macro > inject malicious payload > macro executes

**Visual Basic for Apps (VBA)**
- automates processes within Windows apps
- interacts with OS
- e.g. CVE-2010-0815, VBA does not properly search / filter for ActiveX controls in document (attackers can run arbitary code embedded in doc)