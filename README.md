# Multi threading with Windows Forms

Sample code for article:

Multi threading with Windows Forms

Published at: http://www.codeproject.com/Articles/631514/Multi-threading-with-Windows-Forms

I've come across a requirement on a number of occasions to produce a Windows application that interacts with a remote web server. The Windows application may be dealing with a web-service, or simply automating form input or screen scraping - what is common is that there is one side of the equation that is web based and therefore can potentially handle multiple requests, thus allowing us to complete the process faster. This article is a project that consists of two parts: a threaded Windows client, and a simple MVC application that it interacts with. As not all remote services allow multiple connections, the project gives the option for running the process in sequential or parallel (threaded) mode. The source code of both projects is attached.
