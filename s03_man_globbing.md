# Commmand line tutoiral - Session 03: Discovering commands
## Structure of a command, getting help, manipulating multiple files.

## Topics covered
0. Commands
	- file
	- cat
	- wc

1. Discovering commands
	- type
	- which
	
2. Command structure
	- cmdname [cmd_options] [cmd_arguments]

3. Getting help
	- help (for builtins)
	- --help option
	- info
	- man command
		- navigating man pages
		- searching in a man page
	- apropos
	- whatis

4. Globbing
Wildcard characters can be used to match multiple files.  
	- \*	(matches any string)
	- ?	(matches one character)
	- []	(matches any one of given characters)
		- ^	(inverse the pattern)

5. Exercises
	- Make it a rule to know at least 4-5 options of every command you encounter.
	- list the files in your home directors in long form sorted by time of modification.
	- list the files in your home directors in long form sorted reversely by time of modification.
	- what does the -p option in mkdir command do? use it.
	- what does the command 'head' do? use it.
	- what does the command 'tail' do? use it.
	- from the /bin directory, list all files whose name starts with 'less'.
	- from the /bin directory, list all entries whose name contains a digit.
	- from the /bin directory, list all entries whose name does not contain a vowel.
	- from the /bin directory, list all files whose name consists only of two letters.
	- make a directory called temp1 and copy all files from /bin director whose name starts with a 'b' or a 'p' into it. Verify that the operation was correctly performed and then delete all the files from temp1.
	- make a directory called temp1 and copy all files from /bin director whose name starts with a 'b' or a 'p', and ends in an 's' or 'e' into it. Verify that the operation was correctly performed and then delete all the files from temp1.
