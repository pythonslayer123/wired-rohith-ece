# Bandit Writeups - Rohith AP


## *Note:* 
Passwords mentioned here are the passwords that I got by completing that 	particular level, and not the one used for logging in to that level.
Apologies if the writeups are not appropriate(too short or long) or if the format is messy/ not correct. - ***Rohith***




Level 0: 

	The very first time I looked at the bandit challenges, I was taken aback 	because none of the terms were familiar to me and they all seemed alien. So I decided to learn a bit of computer networking so that I could understand terms like SSH, Ports, Protocols, Networks and stuff like that. That 2 hour long video was quite helpful and I was able to finally understand 	(just the basics) of networking and how things like ports and stuff work.

    And I watched a couple of walkthroughs on YouTube to get started. That Is how I cleared this level.

**Password that I got by completing this lvl:         ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If**


Level 1:
	
	I learned some basic commands like cat, ls, cd, etc. before getting started with this level. I used ls for this level. But to open the file named ‘-’ I had to look it up on the internet. 

    Also figured out that ctrl+c and ctrl+v doesn’t work in the terminal, and that we have to use ctrl+shift+(c/v) instead.

    Used the cat command to open the readme file which had the password to the next level

**Password: 263JGJPfgU6LtdEvgfWU1XP5yac29mFx**

Level 2:
	
    This level had the password stored in a file which had many spaces in its name. 

	I learned how to use quotes(‘ ‘) to locate files that have spaces in their name. 

    And then used the same cat command to open the file.

    

**Password that I got by completing this level: MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx**

Level 3:

	Used the cd command for the first time. 
    
    Also used the flag -a along with the ls command to display hidden files. 

    The cd command can be used to change directories.
    
    Specifying the path of the directory opens that particular directory. Whereas, using just the cd command gets us back to the home directory.

    Learned the difference between dir and ls commands.



**Password: 2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ**

Level 4:

	Used cat ./* first to read the content of all the files within the inhere directory. 
    Then tried the find command to list the type of file, and found out the only readable file within the directory which had the password to the next level.

    Using find ./* command is a much better approach towards this question, because first finding the specified file type first is much easier.



**Password: 4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw**


Level 5:

	Learned about the man command used to open the manual of any terminal command.

    Went through the manual of find command to filter out the files according to the given conditions of the file containing the password. 

**Password: HWasnPhtq9AVKe0dmk45nxy20cvUa6EG**

Level 6:

	Learned about different flags used along with the find command. Eg, user, group, size, etc.

    Also learned how to redirect standard input/ output / error messages.

    Learned that using the ‘/’ character with the find command searches the entire root directory. 

**Password: morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj**

Level 7:

	Learned about the grep command from the man page and used it to locate the password within the data.txt file. 

    The grep command is used to look for patterns within the given file.

    Used this command to search for the word 'millionth' 

**Password: dfwvzFQi4mU0wfNbFOe9RoWskMLg7eEc**

Level 8:

	Learned about piping and how it works. Piping can make things really time efficient in situations like this level. 

    Learned about the uniq command and it’s flag -u. Learned about the sort command. 

    The uniq command works by comparing the preceding and succeeding lines with the current line and removing redundant content. So for this to only print the unique line, the content has to be first sorted, and matching lines have to be next to each other. 
    For this the sort command can be used.

    And to save time and memory, piping is used here to directly feed the sorted output to the input of the uniq command. 

**Password: 4CKMh1JI91bUIZZPXDqGanal4xvAg0JM**

Level 9:

	For this level, I first went through the manual of strings command, and understood that it is used to extract the printable content from the given file. 
    So then I used piping and fed the output of this command to the grep command to filter out the content that did not have a series of ‘=’ signs in it. 
    This command gave only four outputs, from which finding the flag was pretty easy and obvious.

**Password: FGUW5ilLVJrxX9kMYMmlN4MgbpfMiqey**

Level 10:

	Starting out on this level, I went through wiki to know what base 64 is. I then understood that it is a system that converts binary data into a sequence of printable characters. 

    After this point, the level was pretty straightforward and easy because by going through the manual of the base64 command I got to know that the -d flag can be used for decoding the given base64 data. And that directly led me to the password for the next level.

**Password: dtR173fZKb0RRsDFSGsg2RWnpNVj3qRr**

Level 11:

	Learned about the tr command, its synopsis(format) and how it is used to modify/ translate data. 
    Also had a brief glimpse at Rot13, and understood what it is and how it works.

    Used the tr(translate) command to switch 13 places. 

**Password: 7x16WNeHIi5YkIhWsfFIqoognUTyj9Q4**

Level 12:
	
	Went through a walkthrough on YouTube to fully understand this level. 

    Learned the basics of hexdump and what it is. Used the mkdir command for the first time in these challenges, and created a new temporary directory to work with the hexdump.

    Came across the cp command and figured out about it from the manual. Used it to make a copy of the file ‘data.txt’ to the newly created temporary directory.

    Checked the manuals of all new commands and found out that the xxd command is used to create/ reverse a hexdump. Went through the manual further to locate useful flags.

    Used the mv command to move, rename files.

    Learned about the gzip and bzip2 compressions, and also their extensions which are .gz and .bz2 respectively. 

    Learned about the tar archiving system, and its extension (.tar). 

    Performed repeated decompressions and extractions to finally get to the original file that contained the password to the next level.

**Password: FO5dwFsc0cbaIiH0h8J2eUks2vdTDwAn**

Level 13:

	This level seemed pretty new and tough to grasp because of the new way of logging into the server using a key rather than the regular password.

    Learned about the -i flag of the ssh command which is used to give the key to establish a connection. 

    Also came across the term localhost. I had some doubts regarding this level and how this mechanism works, cleared them by watching YouTube tutorials.

**Password: MU4VWeTyJk8ROof1qqmcBPaLh7lDCPvS**

Level 14:
 
	Learned about the telnet command and its synopsis to submit the password to the given port. 

    Submitted the password and then got the password for the next level from there.

**Password: 8xCjnmgoKbGLhHFAZlGE5Tmu4M2tKJQo**

Level 15:

	Learned about SSL/TLS encryptions. Used the manual page of openssl command and found the s_client sub command. 
	
    Then used the openssl, s_client commands to connect to the given port number on localhost.

**Password: kSkvUpMQ7lBYyCM4GBPvCvT1BfWRy0Dx**

Level 16:

	This level required a lot of searching through the manuals, other resources, etc. This is probably the hardest level I had faced in this challenge so far. 

    Got confused and went through the same manual pages again and again hoping to find the right command to search for the ports. Finally found that the nmap command can be used. 

    Then used the nmap command to search through the given range of ports. And ended up with 5 possible ones. Then by hit and trial, I found the correct port number. 

    This is where I encountered the biggest obstacle of this level, and it took a lot of time to figure out. 

    When connecting to the port using openssl s_client, I kept getting a KEYUPDATE message, and couldn’t figure out why it happened or what to do. 
    
    Then went through the manuals over and over again before coming across the -quiet flag. This solved the issue. Now rather than getting a password directly I got a private key to login to the next level. 

    The next couple of steps were very similar to one of the previous levels where we use the key to login. First the key was copied and written into a file in the home directory. And then using the -i flag for ssh command, I logged into the next level.

**Password: EReVavePLFHtFlFsjn3hyzMlvSuSAcRD**



Level 17:

    Learned about the diff command and how it is used to find the unique content between the given files.

    Used the man page for this command to find the synopsis of this command.

    Finally used (diff passwords.new passwords.old)
	 

**Password: x2gLTTjFwMOhQ8oWNbMN362QKxfRqGlO**


Level 18:

    I had absolutely no clue what had to be done in this level to stop that ‘Byebye’ message. 

    Tried going through the man page for ssh command, but couldn’t find anything useful. 

    Watched a YouTube video to understand how to clear this level. 

    We had to stop the .bashrc from getting executed, so we add the command to be executed(which is cat readme) at the end of the usual ssh command that we use to connect.

    As per my understanding, this stops the machine from connecting to their server interactively and just sends the command we give and fetches the output.
**Password: cGWpMaKXVwDUNgPAVJbWYuGHVn9zl3j8**

Level 19:
    
    (Got help from google,YT to solve this level)

    Learned about setuid from the provided wiki resource, and learned how to execute such a file. 

    Ran the command as another user(bandit 20) as was mentioned. Combined it with the cat command to get the password for the next level.

**Password: 0qXahG8ZjOVMN9Ghs7iOWsCfZyXOUbYO**

Level 20:

    Learnt about the nc command from the man page, and how it is used to transfer data between two networks. 

    I did not know how to proceed further in this level, so I reffered to a YouTube walkthrouh to understand what had to be done. 

    From what I understood, we are basically required to open a connection with ourself using the nc command and its flags -l, -v and -p.
**Password: EeoULMCra2q0dSkYj561DX7s1CpBuOBt**

Level 21:

    Learned about the cron method. Understood that it is used to automatically run commands 

    Did not understand this level completely, still have some doubts on the cron system. 


---
## ~Thank you
    
