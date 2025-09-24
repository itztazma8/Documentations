# Architecture
<br>
This is the proposed architecture
<img width="729" height="160" alt="image" src="https://github.com/user-attachments/assets/a9bfef26-8015-428a-82d5-cfa60afd9ba9" />

# Data Transmission
The problem of data transmission has been handled by sending data in small chunks. This way, the problem of sending big data and also at the same time can be solved.

# Thread Safe Memory Allocation
The highlighted feature of this whole system is this. This is used to allocate memory for threads in a safer way so that they do not accidentally come across one another while maintaining the communication needed for certain tasks. Read about the details of the mutex and other stuff in the document!

# Buffer
The famous producer-consumer buffer model has been used here to maintain this safe allocation of tasks. 

