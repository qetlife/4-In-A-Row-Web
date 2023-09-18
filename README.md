# 4-In-A-Row-Web
School Project

ONLY WORKS ON MAC OR LINUX 

For windows you need to change the way the xml is transmited through to the Server/Player.
Windows uses '/n/r', MAC and LINUX uses '/n'. In The class UserXmlWriter, you have two methods readFullXML and sendFullXML. 
Those need to be tweeked around for Windows users.

Console vs Console:
1. src/main/java/TP1/Servidor.java #RUN Servidor.java, this is the server
2. src/main/java/TP1/Jogador.java  #RUN Jogador.java as Java Application for Player 1
3. src/main/java/TP1/Jogador.java  #RUN Jogador.java as Java Application for Player 2
4. Login windows will pop up. You either login or register a new account.
5. Play

Console vs Web:
1. src/main/java/TP1/Servidor.java #RUN Servidor.java, this is the server
2. src/main/java/TP1/Jogador.java  #RUN Jogador.java as Java Application for Player 1
3. src/main/webapp/start_menu.jsp #RUN start_menu.jsp on Server (for example Apache Tomcat) for Player 2 (Do the other way around for P1)
4. Login window will pop up on console, and a login page will pop up on web. Login or Register a new account
5. Play


Player records will be stored in src/main/webapp/Users.xml.
