= Financial Information eXchange (FIX) Message Parser =
http://fixparser.googlecode.com/

net.java.fixparser.SimpleFixParser is non-validating FIX parser written in 
Java (generated  with JavaCC http://javacc.dev.java.net/). It allows empty
tags and does not use data dictionary to parse incoming messages. It is
implemented with the idea to parse FIX messages with maximum
performance and keep them in a form suitable for saving into database.

*Runtime Requirements:*
    JDK 1.5.x

*Build Requirements:*
    JDK 1.5.x, Apache Maven 2.0.x.
    
*JavaCC Grammar:*
	fixparser-x.x.x/src/main/javacc/net/java/fixparser/SimpleFixParser.jj     

Building Instructions and Getting Started Wiki Pages can be found at
http://code.google.com/p/fixparser/w/list.

For more information about FIX Protocol see http://fixprotocol.org/.
