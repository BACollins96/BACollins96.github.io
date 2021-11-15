[Back to Portfolio](./)

Project 2: HTML Parser
===============

-   **Class: CSCI 315** 
-   **Grade: 100**
-   **Language(s):C++**
-   **Source Code Repository:** [Project 2: HTML Parser](https://github.com/BACollins96/csci-315-project2)  
    (Please [email me](mailto:bacollins1@csustudent.net?subject=GitHub%20Access) to request access.)

## Project description

This is a basic HTML parser that goes over an HTML page and sees if it is balanced by checking if it's opening and closing tags. In addition it checks if it can go to any additional pages and connects and see if those are balanced, and keeps a store of where it has been to prevent backtracking. The reason why it is basic is that the structure only allows it to recognize a certain limited number of tags.

## How to compiles / run the program

```
Use ./html-parser on contents of pages directory 
or any other .html file. Use "make" to 
create executable if necessary
```

## UI Design

This is a basic executable file that it performed on existing html files like in Fig. 1. It does this by going through that file character by character and identifying the tags that are in it, finding open tags, storing them and then carrying the top-most open tag to a new closing tag, and determining balance if the stack is empty by the end or if the closing tags are correct to establish if it is balanced. If it notices other html links using auth, then it goes to it and sees if it is balanced, and stores the llink to prevent backtracking.

![screenshot](Seniorscreenshots/Screenshot(94).png)

Fig 1. The code working on the contained html files

