This repository contains all the .jar files and its dependencies to run the World of Balance client.

The .jar files contain code necessary to create servers and run game servers for lobby and each mini game. The .jar files are generated from the World of Balance servers.

Deploying can be done by transferring the contents of this repository to a remote server and running the following command:

`java -jar wob-server.jar`

It is very important that all dependencies for the jar file to run to be contained in the same folder as the jar file. Dependencies could be library jar files, conf files, and other server jars.