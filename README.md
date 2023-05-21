# A1

1.  javac command 
2.  rmic AddServerImpl ---> AddServerImpl_Stub.class file.
3. Copy AddClient.class, AddServerImpl_Stub.class, and AddServerIntf.class to a directory on 	the client machine.
4.. Copy AddServerIntf.class, AddServerImpl.class, AddServerImpl_ Stub.class, and AddServer.class to a directory on the server machine.
5.  rmiregistry
6. Start the Server using java AddServer in new terminal
7.Start the Client java AddClient servername/ip_address 8 9  in new terminal where servername is first arguement and 8 , 9 are second & third arguement respectively
