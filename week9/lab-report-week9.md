# Lab Report 5

I've decided to write a bash script that reproduces lab 4.

Here is a screenshot of the working bash script: ![code](code.png)  

Reproducing mosting of these steps in bash were pretty easy. For example, git clone, add, push, commit, and running tests with java are straightforward and I just pasted these commands into my file in the proper order.

One problem I had was getting my other commands to run after the initial `ssh cs15lwi23akb@ieng6.ucsd.edu`. I simply asked ChatGPT to show me how to run multiple bash commands on a remote server and it showed me how to use `<< EOF` after my ssh command to run the following commands on ieng6.

My next problem was using nano with bash since in lab 4 I had to press the right arrow to navigate ListExamples.java. I asked ChatGPT to show me how to edit line 43 of a java file. It showed me the `sed` command, specifically giving me this code: `sed -i '43s/.*/new string/' file.java` in which I replaced "new string" with "     index2 += 1;" (which is what I want line 43 to read) and "file.java" with "ListExamples.java"

The rest of my code is copied from my lab report 4. These were the lines that I entered into the terminal but now just ordered in a bash script.

Running my code gives this working output:
![ss1](ss1.png)
![ss2](ss2.png)
