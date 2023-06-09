# Lab Report 3

## Researching Commands for `grep`

**1. `grep -e`**  
 

What it does : `grep -e` specifically prints one or more types of patterns that are seperated by newlines. This is useful when searching wihtin input files, or even selcting lines that match one or more patterns. A case can be trying to find a key word within a specific `.txt` file as shown below with the word `limit`.

  * Example 1: 
      ![Image](grep1.png)
  * Example 2:
      ![Image](grep2.png)

**2. `grep -v`**   


What it does : `grep -v` prints out all the lines in the pattern that are not the same (**DO NOT MATCH**). This is useful to use when you can list all the files that do not have a specific word in which you want to avoid. A case can be seen with the word `Introdutcion` shown below as it is not seen when using this command.

  * Example 1: 
      ![Image](grep3.png) 
  * Example 2:
      ![Image](grep4.png)

**3. `grep -c`**  


What it does : `grep -c` specifically prints out only the lines of the count that match that pattern. This is useful to use when trying to see how many lines in a file have a certain word or phrase. A case can be used when trying to see how many times `suggest` is used and could possibly be replaced with other words if used too much.

  * Example 1: 
      ![Image](grep5.png)
      
  * Example 2:
      ![Image](grep6.png)

**4. `grep -n`**  


What it does : `grep -n` prints out the matching lines and their matching line numbers. This is useful to use when trying to find the spefic location of a certain word or phrase with its corresponding line number instead of searching an entire file. A case can be seen if a certain section of a file needs to be highlighted/found for any reason, a quick easy search as shown below with the word `circulation`.

  * Example 1: 
      ![Image](grep7.png)
      
  * Example 2:
      ![Image](grep8.png)

## How were these commands found?

When trying to find the differnt commands that can be used with `grep` you can do a web search or you can ask 
the built-in command function on your terminal. In your terminal you type `man grep` which `man` is short for
"manual". This `man grep` command will allow you to see all the information about that specific command. This 
is where we were able to find the follwoing different ways to use `grep` command. Examples : `grep -e`, 
`grep -v`, `grep -c`, and `grep -n`, are a few of the many to use from!
