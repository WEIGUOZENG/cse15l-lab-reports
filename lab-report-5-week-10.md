
I add a line in the code to print the name of the testfile after printing links in it.
Thus, using `diff` for results.txt of the two markdown-parses, I found there is a difference betweeen the results in line 106 of results.txt which is test-file194.
Output of my code is [baz] and of joe's code is [].
Both of our code have mistakes since the expected output should be [my_(url)].

# MY CODE:
![image](code.png)
## To give the expected output for this testfile:
I should change the while loop to find semicolon after the last close bracket after the first open bracket and use `toReturn.add(markdown.substring(semicolon + 1, closeParen+1));` whhere 'semicolon' will be the index of semicolon.
