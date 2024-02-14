# **Part 1**
![image](https://github.com/dsoto0125/cse15l-lab-reports/assets/156368824/30ab5ad4-b367-407e-a44e-f07f98452c73)
![image](https://github.com/dsoto0125/cse15l-lab-reports/assets/156368824/9e027a4f-cd01-42ea-afd9-75e44cf7665a)

This is the code before and after it has been fixed. I chose the arraylists methods and their tests.

![image](https://github.com/dsoto0125/cse15l-lab-reports/assets/156368824/7a787cf3-c811-4ece-93e2-0a704f66091a)

This is two inputs that induce different results. The first input works as intended in order and returns the reverse order according to the test. The second test however does not return correctly as the return type is int and the input has a null in it, if the person inputting their numbers to the array does not input the correct return type then the code does not post.

# **Part 2**
`grep "pattern" filename`
grep pattern finds us a pattern inside of a file by specifying a pattern and gives us that pattern within the file but without a pattern it exits.

`grep "pattern" file1 file2 file3`
grep pattern within multiple files will do the same process as a singular file, however it does all the files instead.

`grep -r "pattern" directory`
This grep looks for patterns within a directory, in short it looks for similarly named files or types of files using the given pattern within a directory.

`grep -i "pattern" filename`
grep with ignoring pattern means it will look for the pattern but no matter the case, meaning that whether capatalized or not, it will be returned in the final return of grep.

`grep -n "pattern" filename`
grep with `-n` searches through the file with numberlines attached to the pattern found in the file.

`grep -v "pattern" filename`
`-v` changes the pattern search to instead find all lines that do not contain this pattern.

`grep -E "pattern" filename`
Extended within the command line gives us the option to use the pattern search with new characters such as "|,+,?,{}" within a file.

`grep -c "pattern" filename`
grep count will return the amount of lines within a file.









## *ChatGPT logs*
>can you tell me grep and its command line options/alternate ways to use it?
### ChatGPT
>Certainly! grep is a command-line utility in Unix and Unix-like operating systems used to search for patterns in text files. It stands for "global regular expression print".

>Here are some common command-line options for grep:

`-i (or --ignore-case): Ignores case distinctions in both the pattern and the input files.`
`-v (or --invert-match): Inverts the sense of matching, selecting non-matching lines.`
`-r (or --recursive): Recursively search subdirectories listed.`
`-E (or --extended-regexp): Interpret pattern as an extended regular expression.`
`-l (or --files-with-matches): Suppresses normal output; instead, print the name of each input file from which output would normally have been printed.`
`-n (or --line-number): Prefixes each line of output with the 1-based line number within its input file.
Here are a few examples of how you can use grep:`

>Search for a specific pattern in a single file:

>perl
>Copy code
>grep "pattern" filename
>Search for a pattern in multiple files:

>perl
>Copy code
>grep "pattern" file1 file2 file3
>Search for a pattern recursively in all files under a directory:

>perl
>Copy code
>grep -r "pattern" directory
>Search for a pattern ignoring case:

>perl
>Copy code
>grep -i "pattern" filename
>Search for a pattern and show line numbers:

>perl
>Copy code
>grep -n "pattern" filename
>Search for lines not containing a pattern:

>perl
>Copy code
>grep -v "pattern" filename
>Search for a pattern using extended regular expressions:

>mathematica
>Copy code
>grep -E "pattern" filename
>These are some of the basic options and usage examples of grep. There are many more options available, and grep is a powerful tool for text pattern matching in Unix-like systems.

>is there an 8th one?
### ChatGPT
>Apologies for the oversight. Yes, there is another commonly used option for grep:

`-c (or --count): Instead of printing lines that match the pattern, it prints only a count of matching lines.
Here's an example of how to use it:`

>perl
>Copy code
>grep -c "pattern" filename
>This will output the count of lines in the file filename that contain the specified pattern.






