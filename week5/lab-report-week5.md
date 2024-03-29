# Lab Report 3

I chose to look at the `find` command.

### -iname  
(found at [this website](https://www.redhat.com/sysadmin/linux-find-command))  
`-iname` searches for a file by approximate name, meaning that it is not case sensitive.

![iname1](iname1.png)  
In this example, I use `-iname` to to find a txt file that contains "algarve". Even though "algarve" is not their whole name they are capitalized, the real files are still spit out. This is useful because I don't have to know the exact file name or capitalization.

![iname2](iname2.png) 
Similar to the example above, I use iname to find a file that contains both bermud and history. Again, `-iname` allows the real file to show up, even though it is capitalized. I also don't need to know that there is a `-` in the name because I used `-iname` and connected the characters that I knew were in the name together by a `*`. This is useful to find a file that you know multiple parts of but not the whole name.

### -type  
(found at [this website](https://www.redhat.com/sysadmin/linux-find-command))  
`-type f` shows the full path of the all of the files that it finds.

![type1](type1.png)  
In this example, I use `-type f` to display the path of every file in the non-fiction folder. This is useful if you need to copy paste a path.

![type2](type2.png)  
This example also uses the `-type f` command but it combines it with the `-name` command. This is useful for displaying the path of a specific file for a quick copy/paste.

### -size  
(found at [this website](https://www.tecmint.com/35-practical-examples-of-linux-find-command/))  
`-size` shows files that are a specified size.

![size1](size1.png)  
Here I use `-size` to look at files greater in size than 100kB. By using a "+" before "100kB" it only displays files that are greater than 100kB in size. This is useful to find files that are especially large or small.

![size2](size2.png)  
This example uses `-size` to look at files both greater than 100kB and less than 110kB. I use the command twice to set the lower and upper bound on the size. Combining multiple commands is useful to find files of a very specific size.

### -mtime  
(found at [this website](https://geekflare.com/linux-find-commands/))  
`-mtime` shows files that were modified some time ago.

![mtime1](mtime1.png)  
This example uses `-mtime` to look at files that were modified 5 days or longer ago. The number following `-mtime` indicates how many days ago you want to look at and "+" or "-" indicates more or less than that number of days. This is useful to look at files that are espcially new or old. The entire output could not fit into the screenshot.

![mtime2](mtime2.png)  
This example uses `-mtime` to look at files that were modified between 5 days and 10 days ago. I use the command twice to indicate the lower and upper bound. This is useful if you want to find all the files modified on a specific date or range of dates. Since everything in this directory was modified at the same time, this command's output is nothing on my computer.

