# Commmand line tutoiral - Session 04: Know thy shell!
## Get to the shell environment better.

## Topics covered
0. commands.
	- echo
		- double quotes
		- single quotes
	- sort
4. Environment variables.
	- env command
	- shell
	- home
	- user
	- path
	- prompt
	- creating variables
4. Running commands.
	- command terminators
		- new line
		- ;
		- &
	- process IDs
	- DELETE (ctl-c)
	- STOP (ctl-z)
	- return codes
	- &&
	- ||
0. stdin, stdout, stderr
	- reading from stdin
	- ctl-d (end of input)
1. IO Redirection.
	- directing stdout
	- directing stderr
	- directing both
	- directing stdin
2. Pipes.


Y. Exercises (using one line of shell commands except putting text into the file)
1. Create a file by redirecting the output of echo command into it. The append a few more lines of text to that file. Verify the file contents.
2. Create a file by redirecting the output of echo command into it. The append a few more lines of text to that file. Print the contents of the file sorted alphabetically.
3. Create a file by redirecting the output of echo command into it. The append a few more lines of text to that file. Create sorted version of the file which contains the same lines but in sorted order.
4. Create a file by echoing numbers into it. Sort the file contents numerically.
5. Run the sort command so that it takes its input from STDIN instead of reading from file. Enter some numbers to its STDIN and sort should print them in descending order.
6. Change your prompt to something you fancy (save the old one in some variable for restoring it later).
7. Change your PATH variable to something different. (save the old one in some variable for restoring it later). See if you can run commands now.
9. Print the number of entries in the /bin directory.
8. Print the entries in the /bin directory in descending order.
10. Print only the top 5 the entries (in descending order) in the /bin directory.

X. Refrences
1. [(perhaps) the most famous pipeline in CS history!](http://www.leancrew.com/all-this/2011/12/more-shell-less-egg/)
