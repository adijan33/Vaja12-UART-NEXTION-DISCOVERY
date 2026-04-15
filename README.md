# Vaja12-UART-NEXTION-DISCOVERY
2.d)
Izpiše se z0

g) 
objname-b0

c) 
RX- PA3
TX- PA2
RX pin na STM-u moramo povezati s TX pinom na Nextion zaslonu in obratno.

d)
PC0- kanal IN10
4. e) 
Gre za enojno/single ADC pretvorbo.

Tabela ASCII:

ASCII znak   Dvojiško Šestnajstiško Desetiško:
----0------0011 0000------30----------48
----1------0011 0001------31----------49
----2------0011 0010------32----------50
----3------0011 0011------33----------51
----4------0011 0100------34----------52
----5------0011 0101------35----------53
----6------0011 0110------36----------54
----7------0011 0111------37----------55
----8------0011 1000------38----------56
----9------0011 1001------39----------57

Zapis 0xff predstavlja standardno zaključno zaporedje pri komunikaciji z Nextion zasloni. Zaslon začne ukaz obdelovati šele, ko prejme to zaporedje.



Slika vezja
<img width="396" height="454" alt="image" src="https://github.com/user-attachments/assets/bde3dd8d-cd53-4b62-8ab7-cf2670b72891" />



Slika pinout

<img width="715" height="562" alt="image" src="https://github.com/user-attachments/assets/f03be1a6-5acc-49bb-9c6d-3ff3fb924f9c" />



