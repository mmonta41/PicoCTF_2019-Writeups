-CSS on a page is static 
	-simply declarations 
-Javascript however is dynamic on a webpage , although it is all clientside. (all withing the browser[chrome/firefox/edge/etc])
-We start by viewing page  source 
- We see the first part of the flag 
-So lets go ahead and make a directory for the challenge 

`$ mkdir inspector`

we make a flag.txt file and continue to search through the file 

We are looking through some links that could possibly be a hint. The first href is a link to a google api for font (external not part of the challenge so not interesting)

the next href is to css file
- there is comments in css and javascript with following syntax
- `/* */`
- and we see next part of flag in our .css file 
- we move on to continue enumerating and sure enough in our .js file we have the last part of the flag 
- woo hoo 

-next john is going to show us some cool automation

-first we use mv inspector{,_complete} to rename the file 
-`**A simple way to rename files in Linux is with the mv command (shortened from “move”)**. Its primary purpose is moving files and folders, but it can also rename them, since the act of renaming a file is interpreted by the filesystem as moving it from one name to another. “filename1`

-creating script to add `_complete` to end of challenge 
directorys automatically 

-see attached script ~~

 set it to opt with alias and bingo were set

