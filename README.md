# StranikS_Scan-Server
Configuration files provide access control to the online- and NAS-servers and its resources for the programs and other sources. While providing the ability to change addresses and control access to the server.

### Description
Format of the **ini**-file:
* Section **"SYSTEM"**
1. *Version* - version of the configuration files
2. *Status* - server status (0 - is available, 1 - is stopped, 2 - in the process of updating and rebooting)
3. *Date* - last date of updating the configuration files
* Section **"LOCATION"**
1. *Server1*, *Server2*, ... - domains and ip-addresses


