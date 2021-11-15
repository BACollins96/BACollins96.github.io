[Back to Portfolio](./)

Project 1: UPS Image Transfer
===============

-   **Class:CSCI 332** 
-   **Grade:100**
-   **Language(s):C++**
-   **Source Code Repository:** [UPS Image Transfer](https://github.com/BACollins96/csci-332-project)  
    (Please [email me](mailto:bacollins1@csustudent.net?subject=GitHub%20Access) to request access.)

## Project description

Custom client sends a image file to the server to recieve it, which is then listed as recieved. This is done by cutting it into smaller 1000 byte chunks and sending it over to the server, which will receive and reconstruct the image into a copy of that image with the name "Received_[randomcharacters]".

## How to compiles / run the program

How to compile and run the project.

```
Use ./Client_task1.out and ./Server_task1.out
inside of Task1 Server, at the same time, 
starting with ./Server_task1.out connect to 
ip address and send a picture to receiver
```

## UI Design

Using a basic terminal display, both sides of the program, server and client, will use user input to determine network conditions for this to work in. For the server side (see Fig. 1), You will input the listening port that will be listening for the client side connection. Then the client side will decide the server port (see Fig. 2), as well as the ip address of the network to connect to. Once that happens, choose the image file to send over. It will then send it to the server. You can then see that you have received a cute cat from the client (see Fig. 3).

![screenshot](Seniorscreenshots/Screenshot(95).png)

Fig 1. Shows the Server side executable in action


![screenshot](Seniorscreenshots/Screenshot(96).png)

Fig 2. Shows the Client side executable in action

![screenshot](Seniorscreenshots/Screenshot(99).png)

Fig 3. Shows a cute cat that was sent to a client
