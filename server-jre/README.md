# Oracle Server JRE with Debian

* Based on [OracleJava](https://github.com/oracle/docker-images/tree/master/OracleJava)
* Instead of oraclelinux, we used Debian
* Download [Server JRE 8](http://www.oracle.com/technetwork/java/javase/downloads/server-jre8-downloads-2133154.html) file and drop it inside this folder.
* Build:
	`docker build -t mental/server-jre .`