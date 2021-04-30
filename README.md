# Linux_commands

## How to check Hidden files and directories
- `ls -a`

## The Manual, Flags

## What is a wildecards and How to use wildcards
- `*` - All files
- `.` - Current folder
- `. .` - Up one folder

## How can you do Process managment

## What is currently running on your system

## Killing a process/crashed process

## How to check any process running in Foreground and Background jobs

## How to stop/kill any process running in Foreground and Background jobs
- `sudo systemctl (status | start | stop | restart)` - Manage background services
## How to change permissions with chmod command
- `chmod (+rwx | -rwk)`
## How to check permission for files/dir
- `ll`

## What does 777, 400, 600, r,w,x
- `r` - read permission
- `w` - write permission
- `x` - execute permission
- `777` - read, write and execute for everyone
- `400` - same as 777 but only for the issuing user
- `600` - same as 777 but only for the file owner and restricts all others
## How to use head, tail, sort, nl(number line), wc(word count)
- `head` - prints first 10 lines of a file
- `tail` prints last 10 lines of a file
- `sort` - sorts information in a file
- `nl` - prints a file with numbered lines
- `wc` - print out a word count

## What is pipping and redirection
- `cmd 1 | cmd 2` - Use command 1 and use that output as input for command 2
- `cmd > file` - redirect output into a file and overwrite the contents
- `cmd >> file` - redirect output into a file and append it to the end 

## What is STDIN standard input and output
