Trouble connecting to SQL database?
- in SQL Server Configuration Manager: SQL Server-Network Configuration - Protocolls for yourserver -
	TCP/IP enable - IPALL - dynamic: 0 | TCP-Port: 1433
	finally restart Server!

- another option is to change SERVERNAME variable


Not enough RAM? Decrease variable 'cache_size' in classifier.py source files (default = 1000 MB).
