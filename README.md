# 2c.SIMULATING ARP /RARP PROTOCOLS
## AIM
To write a python program for simulating ARP protocols using TCP.
## ALGORITHM:
## Client:
1. Start the program
2. Using socket connection is established between client and server.
3. Get the IP address to be converted into MAC address.
4. Send this IP address to server.
5. Server returns the MAC address to client.
## Server:
1. Start the program
2. Accept the socket which is created by the client.
3. Server maintains the table in which IP and corresponding MAC addresses are
stored.
4. Read the IP address which is send by the client.
5. Map the IP address with its MAC address and return the MAC address to client.
P
## PROGRAM - ARP
![Screenshot 2025-03-18 205039](https://github.com/user-attachments/assets/00cd1bcf-4e2a-478a-82b5-1ca0e183c466)

## OUPUT - ARP
![Screenshot 2025-03-18 205024](https://github.com/user-attachments/assets/b6599239-3b2c-488b-be4b-6f30f1c10e54)

## PROGRAM - RARP
![Screenshot 2025-03-18 210102](https://github.com/user-attachments/assets/371508a9-4720-4508-8c0e-684234bc7c97)

## OUPUT -RARP
![Screenshot 2025-03-18 210022](https://github.com/user-attachments/assets/61072786-e609-48c0-a23f-236b494b97e9)

## RESULT
Thus, the python program for simulating ARP protocols using TCP was successfully 
executed.
