## Overview
This project is a simple secure file transfer system with a **client** and **server** built in C#.  
The server stores files and responds to client requests.  
The client can **upload**, **download**, and **list** files from the server.

AES encryption is used to protect files during transfer.

---

## Features
- Upload encrypted files to the server  
- Download encrypted files from the server  
- List files stored on the server  
- TCP-based request/response model  
- AES-128 encryption for secure transfer  

---

## How to Run

### Server:
```
dotnet run
```

### Client:
```
dotnet run
```

### Commands:
```
upload <filepath>
download <filename>
list
exit
```

---

## How It Works (Short)
- Client encrypts files then sends to server  
- Server decrypts and saves files  
- Server encrypts files when sending back  
- Client decrypts upon receiving  

AES key and IV are predefined for both sides.

---

## Requirements Met
- Original server code 
- Original client code  
- Request/response model 
- Secure file handling  
- Fully runnable demo

---

## Author
Ernesto  
Secure File Transfer Final Project
