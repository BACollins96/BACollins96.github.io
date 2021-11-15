[Back to Portfolio](./)

Project 4: XV6 Forktest
===============

-   **Class: CSCI 431** 
-   **Grade: 100**
-   **Language(s):C**
-   **Source Code Repository:** [Project 4: XV6 Forktest](https://github.com/BACollins96/xv6-Blake)  
    (Please [email me](mailto:bacollins1@csustudent.net?subject=GitHub%20Access) to request access.)

## Project description

This is a replication of the forktest lab in the xv6 emulated OS environment using qemu. This was done by making a random number generator and generating children processes that would then recieving a random number. However, a problem occurs where it was unable to be kept until the end to compare for the biggest number due to lack some of the C languages key pieces of functionality that made it easier to do. Thus a work around was made as the randomness of the numbers wasn't truly random. There were also edits made to the kernel that are labelled, but do not cause changes.

## How to compiles / run the program

```
Xv6: use make if not already made, then use make qemu or make qemu-nox. 
Use ./forktest  and a number to test forktest(./forktest 6, for example). 
Make sure you have qemu.
```

## UI Design

Opens an emulated terminal which can be used to access the executable files that are made with the Makefile, then the forktest can be used as seen in both figures. Figure one has used the fortest without inputing a button to show the results of that, and then figure 2 shows how it would work using a number, which causes it to run as intended.

![screenshot](Seniorscreenshots/Screenshot(97).png)

Fig 1. Base run of the ./forktest executable inside of a qemu window

![screenshot](Seniorscreenshots/Screenshot(98).png)

Fig 2. Base run of the ./forktest executable with numbers to make it work correctly, inside of a qemu-nox window
