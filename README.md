# Shell-in-C
This is a custom shell in which we can implement the commands word ,dir and date . 
1) **word:**
   - It is a built-in (internal) command, Reads the number of words (assume word is a “space-separated” string) in a text file, and throws an error if the file does not exist.
   - Syntax: `word [-option] [file_name]`
   - Options:
     - `-n`: ignores new line character
     - `-d`: difference between the word sizes of two text files

2) **dir:**
   - It creates a directory, and then changes the path to that directory.
   - Syntax: `dir [-option] [dir_name]`
   - Options:
     - `-r`: removes if the directory already exists and create a new directory instead of throwing an error
     - `-v`: print a message for each step in the running of this command

3) **date:**
   - It returns the last modified date and time of a particular file.
   - Syntax: `date [-option] [file_name]`
   - Options:
     - `-d`: display time described by STRING
     - `-R`: output date and time in RFC 5322 format