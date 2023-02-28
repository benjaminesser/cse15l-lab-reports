# Lab Report 4  

4. Keys pressed: `ssh cs15lwi23akb@ieng6.ucsd.edu` `enter`

This command uses my specific account to log me into the ieng6 remote server.

5. Keys pressed: `git clone ` `<Ctrl-c><Ctrl-v><enter>`

Here I type out "git clone " and then copy the ssh key from the repository on GitHub and paste it into terminal. This clones this repository from GitHub into the home directory of ieng6.

6. Keys pressed: `cd l` `<tab><enter>`, `<Ctrl-c><Ctrl-v><enter>`, `<Ctrl-c><Ctrl-v>` ` L` `<tab>` `Tests` `<enter>`

Here I type "cd l" and then tab which autocompletes to "cd lab7/". This command navigates me to the lab7/ directory. Then I copy "javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java" from the CS15L website and paste it into the terminal. This command compiles all of the java files in lab7/, which is the directory that I am now in. Next I copy "java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore" from the CS15L website and patste it into the terminal. Then I add ListExamplesTests after this (using `<tab>` to help complete the commmand). This command runs the class file called "ListExamplesTests" which contains the tests that fail.
  
7. Keys pressed: `nano +43 L` `<tab>` `.java` `<enter>`, `<right><right><right><right><right><right><right><right><right><right><right><right><backspace>` `2` `<Ctr-o><enter><Ctrl-x>`

Here I use tab to complete the command "nano +43 ListExamples.java". This command opens up ListExamples.java to the 43rd line using the nano editor. From there I press the right arrow 12 times, backspace, and "2" to change index1 to index2. Then I save the file with `<Ctrl-o>` and exit the nano editor via `<Ctrl-x>`. 
  
8. Keys pressed: `<up><up><up><enter>`, `<up><up><up><enter>`
  
The command `javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java` was 3 up in terminal history so I pressed the up arrow 3 times to find it and comiple all the java files in the directory. Then the command `java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ListExamplesTests` was 3 up in terminal history so I pressed the up arrow 3 times to access it and run the passing tests.
  
9. Keys pressed: `git add L` `<tab>` `.java` `<enter>`, `git commit -m "updated"` `<enter>`, `git push` `<enter>`
  
I used tab to autocomplete the command `git add ListExamples.java` which adds the updated java file to the next commit. `git commit -m "updated"` commits ListExamples.java with the message "updated". Finally, `git push` pushes the changes to my forked repository.
