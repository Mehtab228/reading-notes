# Fun With Terminals #

## --- ##

### The Command Line ###

- It is a text based interface system where you can type commands and it will give you a response. If you're on a Mac then you'll find the program Terminal under Applications -> Utilities. An easy way to get to it is the key combination 'command + space' which will bring up Spotlight, then start typing Terminal and it will soon show up

### Basic Navigation ##

- pwd which stands for Print Working Directory. (You'll find that a lot of commands in linux are named as an abbreviation of a word or words describing them. This makes it easier to remember them.) The command does just that. It tells you what your current or present working directory is. Give it a try now

- There are 2 types of paths we can use, absolute and relative. Whenever we refer to a file or directory we are using one of these paths. Whenever we refer to a file or directory, we can, in fact, use either type of path

- ~ (tilde) - This is a shortcut for your home directory. eg, if your home directory is /home/ryan then you could refer to the directory Documents with the path /home/ryan/Documents or ~/Documents

- . (dot) - This is a reference to your current directory. eg in the example above we referred to Documents on line 4 with a relative path. It could also be written as ./Documents (Normally this extra bit is not required but in later sections we will see where it comes in handy).

- .. (dotdot)- This is a reference to the parent directory. You can use this several times in a path to keep going up the hierarchy. eg if you were in the path /home/ryan you could run the command ls ../../ and this would do a listing of the root directory.

## More About Files ##

- This one can sometimes be hard to get your head around but as you work through the sections it will start to make more sense. A file extension is normally a set of 2 - 4 characters after a full stop at the end of a file, which denotes what type of file it is. The following are common extensions:

- file.exe - an executable file, or program.
- file.txt - a plain text file.
- file.png, file.gif, file.jpg - an image

- Linux actually has a very simple and elegant mechanism for specifying that a file or directory is hidden. If the file or directory's name begins with a . (full stop) then it is considered to be hidden

- file
obtain information about what type of file a file or directory is.

- ls -a
List the contents of a directory, including hidden files.

## Manual Pages ##

- The manual pages are a set of pages that explain every command available on your system including what they do, the specifics of how you run them and what command line arguments they accept

- man <command>
Look up the manual page for a particular command.

- man -k <search term>
Do a keyword search for all manual pages containing the given search term.

- /<term>
Within a manual page, perform a search for 'term'

- n
After performing a search within a manual page, select the next found item

## File Manipulation ##

- Creating a directory is pretty easy. The command we are after is mkdir which is short for Make Directory

- The first one is -p which tells mkdir to make parent directories as needed (demonstration of what that actually means below).

- The second one is -v which makes mkdir tell us what it is doing (as you saw in the example above, it normally does not).

- The command to remove a directory is rmdir, short for remove directory

- to create blank files use the command touch

- cp
Copy - ie. Copy a file or directory.

- mv
Move - ie. Move a file or directory (can also be used to rename).

- rm
Remove - ie. Delete a file

[Cheat Sheet for terminal commands](https://ryanstutorials.net/linuxtutorial/cheatsheet.php)
