
# SpeedtestPingService
Just a jar file that binds 49121 udp port after running. It sends back all incoming packets from clients. The client can calculate the connection delay simply by calculating the time between sending and receiving some unique packet.
# How check it
You can check this service with the nping utility included in nmap package. Just execute this command: `nping --udp -p 49121 <address>` and you will see sequence of sended and recieved packets.
