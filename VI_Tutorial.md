* **What is the VI editor?**

The VI editor is the most popular and classic text editor in the Linux family. Below, are some reasons which make it a widely used editor –

   * It is available in almost all Linux Distributions
   * It works the same across different platforms and Distributions
   * It is user-friendly. Hence, millions of Linux users love it and use it for their editing needs

Nowadays, there are advanced versions of the vi editor available, and the most popular one is VIM which is Vi Improved. Some of the other ones are Elvis, Nvi, Nano, and Vile. It is wise to learn vi because it is feature-rich and offers endless possibilities to edit a file.

To work on VI editor, you need to understand its operation modes. They can be divided into two main parts.

1. **Command Mode**
2. **Insert Mode**

   * **Command Mode**
   
   1. The vi editor opens in this mode, and it only **understands commands**
   2. In this mode, you can, **move the cursor and cut, copy, paste the text**
   3. This mode also saves the changes you have made to the file
   4. **Commands are case sensitive.** You should use the right letter case.
   
   
   * **Insert Mode**
   
   1. This mode is for inserting text in the file.
   2. You can switch to the Insert mode from the command mode  **by pressing 'i' on the keyboard**
   3. Once you are in Insert mode, any key would be taken as an input for the file on which you are currently working.
   4. To return to the command mode and save the changes you have made you need to press the Esc key
   
*   Questions to answer:
  
    * **cd**
    
    **cd (directory name)** this command is used to change directories. If you write cd alone, you will move out of the current directory. After using ls (to see the directories), you can write the name of the directory you want to enter.
    
    * **mkdir** 
    
    this command Creates new folders in an instant with this command.
    **Example:** mkdir /Users/jdoe/Desktop/cool_stuff
    
    * **cp**
    
    **cp stands for copy.** This command is used to copy files or group of files or directory. It creates an exact image of a file on a disk with different file name. cp command require at least two filenames in its arguments.
    
     **For Example:**
     cp [OPTION] Source Destination
     cp [OPTION] Source Directory
     cp [OPTION] Source-1 Source-2 Source-3 Source-n Directory

     First and second syntax is used to copy Source file to Destination file or Directory.
     Third syntax is used to copy multiple Sources(files) to Directory.
    
    
    * **pwd**
    
    The basic usage, as is usually the case, is very easy. All you have to do is to run the 'pwd' command without any options, and you'll get the full path to the **current working directory in output.
    
    * **mv**
    
    this command helps us to quickly **move a file or folder into another folder using mv**. It works by simply changing the name of the path.

    The syntax is mv <old file path> <new file path>.

    **For example:**, mv /Users/jdoe/Documents/file1 /Users/jdoe/Desktop/file1 will move file1 from jdoe’s Documents to his Desktop.
    
    * **rm**
    
    This command will delete, immediately and without prejudice, any file you put in its path. Obviously, use it with extreme             caution. Unlike clicking **Empty Trash, rm** will not ask if you’re sure. It assumes you know what you’re doing.

     One thing to note about **rm** is that by default, it will only delete files, not folders. To delete folders, you must use the **-R** option, which stands for **recursive**.

     **Example**: rm -R /Users/jdoe/Desktop/cool_stuff
    
    * **history**
    
    All of our services are currently running on Linux. In Linux, there is a very useful command to show you all of the last commands that have been recently used. The command is simply called history, but can also be accessed by looking at your .bash_history in your home folder.
    
    * **Home** **directory** **and** **~**
    
    To navigate to your home directory, use "cd" or "cd ~"
    
    * **File path in Linux**
    
    Files and folders on Linux are given names containing the usual components like the letters, numbers, and other characters on a keyboard. But when a file is inside a folder, or a folder is inside another folder, the / character shows the relationship between them. That’s why you often see files listed in the format **/usr/bin/python3 or /etc/os-release.** The forward slashes indicate that one item is stored inside of the item preceding it.

Every file and folder on a POSIX system can be expressed as a path. If I have the file **penguin.jpg** in the **Pictures** folder within my home directory, and my username is **seth**, then the file path can be expressed as **/home/seth/Pictures/penguin.jpg.

Most users interact primarily with their home directory, so the tilde (~) character is used as a shorthand. That fact means that I can express my example penguin picture as either **/home/seth/Pictures/penguin.jpg or as ~/Pictures/penguin.jpg.

    * **Using the tab key to complete file paths**
   
   **Tab** is your friend

On a system famous for eschewing three-letter commands when two or even one-letter commands will do, rest assured that no seasoned POSIX user ever types out everything. In the Bash shell, the **Tab** key means autocomplete, and autocomplete never lies. For instance, to type the example **penguin.jpg** file’s location, you can start with:

$ ~/Pi

and then press the **Tab** key. As long as there is only one item starting with Pi, **the folder Pictures autocompletes for you.
      
      
    * **Using up and down arrow for history**
   
   This command helps us to navigate through our history of commands which had been run previously.
