# C-Backdoor

Very Lightweight Backdoor and Keylogger Utility.

There are two parts: Backdoor that have to be executed on target computer and server that will listen for incoming connections. 

This backdoor will execute commands and capture keystrokes. 

COMPILATION COMMANDS:

COMPILING THE BACKDOOR : 

i686-w64-mingw32-gcc -o mlwr.exe backdoor.c -lwsock32 -lwininet

COMPILING THE SERVER :

gcc server.c -o server.c
