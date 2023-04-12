# Linux-CLI
Working with Linux command line interface

Redirection reroutes standard input, standard output, and standard error.

The common redirection commands are:

> redirects standard output of a command to a file, overwriting previous content.
>> redirects standard output of a command to a file, appending new content to old content.
< redirects standard input to a command.
| redirects standard output of a command to another command.
A number of other commands are powerful when combined with redirection commands:

sort: sorts lines of text alphabetically.
uniq: filters duplicate, adjacent lines of text.
grep: searches for a text pattern and outputs it.
sed : searches for a text pattern, modifies it, and outputs it.

Options modify the behavior of commands:
ls -a lists all contents of a directory, including hidden files and directories
ls -l lists all contents in long format
ls -t orders files and directories by the time they were last modified
Multiple options can be used together, like ls -alt
From the command line, you can also copy, move, and remove files and directories:
cp copies files
mv moves and renames files
rm removes files
rm -r removes directories
