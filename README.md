# ServerBenchmarkTest
Extremely vulnerable web applications

This web applications are created for web vulnerability scanning. Therefore they contain very easy exploitable vulnerabilities:
- SQL Injection
- XSS (persistent and reflexted)
- Local File Inclusion
- CMD Injection
- PHP Injection

Only ServerBenchmarkTest_Extended contains all of them. The rest provides SQL Injection and XSS.

Installation requirements (ServerBenchmarkTest, ServerBenchmarkTest_Extended):
- python 3 (additional modules named in pythonPrerequisites.txt)
- php
- mysql (description in mysqlLinux.txt and mysqlWindows.txt)
- javascript

Requirements for apache-bench and wordpress_apache2:
- mysql (same credentials as for ServerBenchmarkTest)
- php
- javascript
- apache2

To start ServerBenchmarkTest and the extended Version just call the script. 
Example for console: python ./httpServer.py (only if you are in the local directory)

For apache-bench and wordpress_apache2 to work you need to copy them into the /etc/var/www/html on kali linux.
Additionally for wordpress_apache2 you have to change the origin directory for apache to the server folder. (Description in wordpress_apache2_README.txt)
