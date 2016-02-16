# LogAnalyser

AIM:
Implementation of an application called "Log Analyzer" in Hadoop environment.

Input file has lines that look like:

 "96.7.4.14 - - [24/Jun/2015:04:20:11 -0400]
   * "GET /cat.jpg HTTP/1.1" 200 12433"


Based on this, the application deduces the number of users per month accessing the server.

So , the output looks something similar to : 
January 23
February 20
March 0
...
and so on..

IMPLEMENTATION DETAILS:

Technical Details: Hadoop framework, NetBeans, Java 7 
PS. Setting up hadoop was a huge task when compared to writing the code ! :D
The project consists of four files, following the Map-Reduce paradigm.    

