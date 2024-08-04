the shellcode is for x64 based archictecture, if your pc is x86 based use - 

msfvenom -p windows/messagebox TEXT="JNE" TITLE="DSCN" -f c

the executable pops up a message box with the specified text and title.

you might want to toggle some windows defender settings as the executable can be flagged (maybe, maybe not).
