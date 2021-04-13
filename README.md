# ServerDevelopementJourney
A simple set of servers that I am planning to build in future to keep a log of my progress throughout my course of learning. 
I will be developing really small but efficient servers on this repo using age old techniques like multi threading. Although most of the servers would be in Java but a few would be in NodeJS as well.
### ThroughOutHttpServer
ThroughOutHttpServer is server that hosts a book and when requested on /search with parameter word assigned some character String . It will find the occurences of those string in that particular book. In this case, I have used pride and prejudice.

### Structure :- 
* It uses A FixedPoolThread to handle multiple requests which stops the server from getting overloaded and maintains a good latency of the application.
* Tested with Apache Jmeter to was able to respond to 2000 requests within 2 seconds
* Simple and efficient
