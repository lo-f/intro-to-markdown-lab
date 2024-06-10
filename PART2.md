# Creating a file using the Terminal

When interacting with computers, users typically navigate using a graphical user interface, or GUI. A less common method is by using a command line interface (CLI), used by programmers and developers. A CLI like Terminal, which is common for macOS users, offers more versitlity and control to programmers, allowing users to create files right from the command line.

![code banner](https://images.unsplash.com/photo-1509966756634-9c23dd6e6815?q=80&w=3176&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D)

## 1. Basic commands

Terminal uses simple commands followed by a term, or argument, to allow users to communicate with computers.

`command [command parameters]`

- **cd [directory-name]**: changes directory to the named directory
- **ls**: lists all the contents of the current directory
- **mkdir [new-directory-name]**: creates a new directory inside of the current directory
- **touch [new-file-name]**: creates a new file inside of the current directory

### ***Example:***

`cd my-projects`

> Tip: The cd command, which stands for change directory, can change to any directory that the current directory is the parent of. But what if you want to change to a directory that is nested further than a directory in the current one? You can simply use the cd followed by the pathway to your desired directory. 
<br>
<br>
`cd parent-directory-1/parent-directory-2/.../desired-directory`

## 2. Create a directory

To create a directory, more commonly called a folder, we use the mkdir command. The mkdir command will make a new directory inside of the current directory.

### ***Example:***

`mkdir new-awesome-app`

## 3. Create a file

Finally, to create a file, we use the touch command. The touch command will make a file inside the current directory.

### ***Example:***

`touch README.md`

To level up navigating your computer using Terminal, be sure to use [mdn web docs](https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Understanding_client-side_tools/Command_line) as a good resource. 

