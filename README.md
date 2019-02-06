## Audio Stream
This program allows you to audio broadcast between server and client. 
In this architecture **Server** is **broadcaster** and **Client/Clients** are **listeners.**
### To execute program 
#### Server
1 = Activate ip_group, this parameter allows you to broadcast to an ip group
0 = Public broadcast
```
python2.7 audio_server.py <server_ip_addr> <port_number> <1 or 0>
```

##### Client
```
python2.7 audio_client.py <server_ip_addr> <port_number>
```

## Video Stream
This program allows you to video broadcast between server and client. 
In this architecture **Server** is **broadcaster** and **Client/Clients** are **listeners.**
### To execute program 
#### Server
1 = Activate ip_group, this parameter allows you to broadcast to an ip group
0 = Public broadcast
```
python2.7 video_server.py <server_ip_addr> <port_number> <1 or 0>
```

##### Client
```
python2.7 video_client.py <server_ip_addr> <port_number>
```


## Video&Audio Stream
This program allows you to video and audio broadcast between server and client. 
In this architecture **Server** is **broadcaster** and **Client/Clients** are **listeners.**
### To execute program 
#### Server
1 = Activate ip_group, this parameter allows you to broadcast to an ip group
0 = Public broadcast
```
python2.7 live_stream_server.py <server_ip_addr> <port_number> <1 or 0>
```

##### Client
```
python2.7 live_stream_client.py <server_ip_addr> <port_number>
```