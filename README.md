# PT3-E019_PeopleSoft_File_Manager
PeopleSoft Development File Manager

PeopleTools Tech Tips    
Randy Groncki

2021-12-02

Developers always need access to the file servers for logs, traces, input and output files. I’ve developed this utility to speed development tasks of managing files associated with PeopleTools project. I’ve used this in several of my videos when I want to show file results of PeopleTools processing.

This utility is NOT meant to be used in Production environments. There are other utilities available, but they tend to be larger and require much more configuration and security maintenance. This utility assumes the user has complete access to the report server as the admin account running the App Server.

This utility sees the directories as per the Application server it’s running. Depending on your implementation architecture, it may or may not see file generated by other App Servers or Report Servers.

This tool is very useful in PUM and development environments where the technology stack is small or even just one server.

### Web Posting: https://peopletoolstechtips.com/peoplesoft-file-manager

### YouTube demo: https://www.youtube.com/watch?v=y9Z7QHzZtwg

### Contact:  
* randy@peopletoolstechtips.com  
* PeopleToolsTechTips@Gmail.com

This file contains all the objects referenced in the video and document.

## PeopleTools Project is using PeopleTools 8.59.04
  * This contains all the components, pages, records and PeopleCode used in the demonstration.
  * The target database must be minimal 8.58 PeopleTools

* X_PT3_019_LOGFILE_UTIL (folder)  
* X_PT3_019_LOGFILE_UTIL.zip  
