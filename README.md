gcc UDPserver.c -o UDPserver
./UDPserver 4455
nc -u 127.0.0.1 4455

gcc UDPclient.c -o UDPclient
./UDPclient 4456 
nc -u -l 4456
