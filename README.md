# writeups-rithika
BANDIT – OVER THE WIRE

## Level 0:
Logged into the game using this command ssh
ls
cat readme

The password for this level is bandit0
## Level 0 to Level 1:
I used the following commands to get the password for this level.

## Level 1 to level 2:
After trying cat “-“ for sometime, I couldn’t access the file so I went through google and
realized that it was taking ”-“ as a synonym . so I used “ ls -l” tolist the information about
the file. And found out this

I used “ cat./” to view the concatenated files.

## Level 2 to level 3:

The commands were similar to the previous level
## Level 3 to level 4:

Few similar commands

Used “ls -a” to list the files and directories
##Level 4 to level 5:
I used the command “file./*” to search for the human readable files

## Level 5 to level 6:

Used the command find to get the files with the given properties.
##Level 6 to level 7:

Using this we can know which files we have access to and for which we don’t.

##Level 7 to level 8:
We used two commands together “cat data.txt | grep millionth”
And got the password

## Level 8 to level 9:

The commands sort and uniq
Sort – orders a list of items both alphabetically and numerically
Uniq – it removes adjacent duplicate lines in a list

## Level 9 to 10:
 I used the command “ cat data.txt | sort | uniq -u
And found a set of ====

## Level 10 to level 11:

A base64 code is given , we need to decode it.
I used cyberchef to decode it

## Level 11 to 12:

A ROT13 text has been given , we need to decode it, I am going to use cyberchef for this.

## Level 12 to 13:
The file was compressed too many times, so each time we unpack and check it.
I used the following commands to play the game:
Gzip: it’s a compressing tool , I used “gzip -d” to truncate the file
Tar: helps extract files

Xfv: used to extract file in archived files
And got the password after multiple trials.

## Level 13 to 14:
I used the ssh -i command to access the bandit14 level
and then used 
' cat /etc/bandit_pass/bandit14 '
to get the passsword for the level 15



