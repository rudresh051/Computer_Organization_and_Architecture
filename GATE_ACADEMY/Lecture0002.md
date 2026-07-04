# Lec #02 Basics Of COA (Part-02)| Computer Organization | GATE 2023 | by Vishal Sir

Memory में Actual Information store कैसे होता है - 

## Endianess Mechanism
Endianess mechanism is used to define the order of storage of bytes in memory  

There are two different endian-ness mechanism
1. Big-Endian
2. Little-endian

3. **Big-endian** - In big-endian mechanism most significant byte of data is stored at **lowest** memory address i.e starting address.

e.g. Consider an hexadecimal no. 3F43 needs to be stored in memory.  

3F - Most significatnt byte  
43 - Least significant byte

* If we need to store this data starting from memory address 1000(in-decimal)
* In big-endian mechanism highest byte of 3F43, i.e. "3F" will be stored at address "1000" and "43" will be stored at address "1001".  

![alt text](image-12.png)

2. **Little-endian** - In little endian mechanism highest  sinificant of data is stored at last memory address

i.e. in little endian mechanism if we want to store hexadecimal no. 3F43 starting from memory address 1000, then "43" will be stored at address 1000 and "3F" (i.e. Most significant byte) will be stored at address 1001  

![alt text](image-13.png)

**what's the reason of above?**    
if want to increase the number e.g. 21 to 421. so if I want to increase the value later, so later you can store 4 in the next position

![alt text](image-14.png)

so you need not to change the already stored bits


![alt text](image-15.png)  
And if you are using big-endian you needed to shift. It's only good for reading and if you want to increase the value using big-endian you need to shift all the previously stored bytes  

Little-endian mechanism is faster to operate  
Modern day system is Little-endian 


