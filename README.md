# Python-Hash-Cracker
Extremely Fast Python Hash Cracker with GUI!!! This tool can try 300,00 words a second!!! It comes in a command line version and a compiled executable windows gui!!!( This tool is faster than Cain www.Oxid.it)
It supportes several hash formats with options like a Numbers Bruteforce and verbose (command line).
#Usage
Command line is fairly straight forword, here are the options:

-h [hash]

-t [type]

-w [wordlist]

-n [numbers bruteforce, used in place of -w]

-v [verbose, slows down cracking time though :(]

#Examples:

Hashcrack with a worddlist and verbose mode:

./Hash-Cracker.py -h 7406e17d2e30b05b7220a800fad53a22 -t md5 -w Wordlist.txt -v

Numbers bruteforce fast:

./Hash-Cracker.py -h 7406e17d2e30b05b7220a800fad53a22 -t md5 -n

#Gui
![Alt text](img.JPG?raw=true "Screenshot")

Select File:Import than 'Hash' or 'Hash from file', than under Import, import a wordlist. Select the hash type and hit crack.
Options include Numbers bruteforce and about. Help is also right there. You can also export the hash, word, and info to a file once it has been cracked.

#Issues with the GUI
When cracking the main window will freeze. THIS IS NOT BAD. It means it realy is running.There is no way to stop this because python threading will not allow it.

#Enjoy
