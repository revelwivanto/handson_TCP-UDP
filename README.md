# handson_TCP-UDP
# TCP
M.Revel 5025211233
![image](https://github.com/revelwivanto/handson_TCP-UDP/assets/116476269/b31df271-718b-41b4-8403-97acf416ee4e)
1. ip = 192.168.86.68, port = 55639
2. ip = 128.119.245.12, port = 80
  ![image](https://github.com/revelwivanto/handson_TCP-UDP/assets/116476269/d4e0adef-86ea-4d7f-a59a-6a77782d65fb)
3. sequence number (Raw) = 4236649187
![image](https://github.com/revelwivanto/handson_TCP-UDP/assets/116476269/93b21146-dd97-4e42-808a-2043994c7b55)
4. sequence number (Raw) = 1068969752, acknowledgement number (raw) 4236649188
![image](https://github.com/revelwivanto/handson_TCP-UDP/assets/116476269/8a7d899c-c6e6-4da1-be69-fa75e8b99a83)
5. sequence number (Raw) = 4236801228, TCP payload =  1385 bytes
6. ![image](https://github.com/revelwivanto/handson_TCP-UDP/assets/116476269/8cd27b55-f11f-4350-a583-85dbf444632a)
arrival time = feb 3, 2021 09:43:26.840 SE Asia
![image](https://github.com/revelwivanto/handson_TCP-UDP/assets/116476269/744be997-caa1-4df0-94f7-64e7f2d5250c)
arrival time 09:43:26.842
![image](https://github.com/revelwivanto/handson_TCP-UDP/assets/116476269/23d3c7d3-1ca9-4332-a735-2ae16d9f242d)
![image](https://github.com/revelwivanto/handson_TCP-UDP/assets/116476269/dfdbb404-8872-4e7f-88ca-134fe754eb7c)
RTT = 0,045050
![image](https://github.com/revelwivanto/handson_TCP-UDP/assets/116476269/db296316-89a8-4877-ae52-e7331bc3049a)
RTT = 0,000107
![image](https://github.com/revelwivanto/handson_TCP-UDP/assets/116476269/573f621f-72c9-4b47-b47a-1fad6cb96585)
7.Header (32) + Payload (1448) = 1480 bytes

# UDP
![image](https://github.com/revelwivanto/handson_TCP-UDP/assets/116476269/54e9ae35-69ba-4499-a29d-6249f25c7284)
1. packet number 42, port 57621, header length = 20 bytes, 4 field pada header UDP: Source Port, Destination Port, Length, Checksum
2. 
3. UDP Header Length = 2 bytes (Source Port) + 2 bytes (Destination Port) + 2 bytes (Length) + 2 bytes (Checksum) = 8 bytes
Total Length of the UDP Datagram = 52 bytes
UDP Data Payload Length = Total Length of the UDP Datagram - UDP Header Length
UDP Data Payload Length = 52 bytes - 8 bytes = 44 bytes
So, in this case, the UDP data payload is 44 bytes in length.
4. It's 65.535 (16 bit field) - 8 (header) = 65.527 bytes
5. Port 65.535
  ![image](https://github.com/revelwivanto/handson_TCP-UDP/assets/116476269/1b08ea47-2e60-4ac5-b55e-69652001ae09)
6. port 17
7. udp packet no 42 with source port 57621 and udp packet no 58 with dst port 54122
