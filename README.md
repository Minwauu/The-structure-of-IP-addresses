# The-structure-of-IP-addresses

IP - Internet protocol - An IP address is a unique number which is used to 'address' / identify a host computer or node which communicates over IP on the internet.

The two versions in use today are ipv4 and ipv6.

![image](https://github.com/Minwauu/The-structure-of-IP-addresses/assets/110039102/bc2aa19b-8af3-46c4-b9d3-50fd3c4c163a)

IPV4 - network identifier and host identifier, 3 bytes, 1 byte. 

A system of classes was used to define the network/ host portions of ipv4 address. The system divided the network/hot parts in a small number of fixed ways. 

Class A - 1 byte, 3 bytes. 
Class B - 2 bytes, 2 bytes. 
Class C - 3 bytes, 1 byte. 

Classless addressing:

- More modern method
- split the address at any point we like
- we can use *subnet masking* along with the IP address to achieve this.

  ![image](https://github.com/Minwauu/The-structure-of-IP-addresses/assets/110039102/1d32aeed-278c-49bc-bd5b-015a5fd9d826)

We can use a subnet mask along with the IP to identify the two separate parts of the address.
Subnetting:
- Often large organisations want to further subdivide their network in smaller subnetwrok segements
- This can improve stability, speed, and avoid unnecessary network traffic and collisions.
- A subnet ID is used, this has to come from the most significant bits from the host ID part of the IP address.

  ![image](https://github.com/Minwauu/The-structure-of-IP-addresses/assets/110039102/9b753ed9-67c1-40e7-8b02-e30dd8e84018)
![image](https://github.com/Minwauu/The-structure-of-IP-addresses/assets/110039102/52818d98-0178-4aaf-88bc-3568dbd82523)

1. 192.169.2.0
2. 192.168.0.0
3. 192.168.252.0
   
