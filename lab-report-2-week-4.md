## changes
![image](change1.png)
![image](change2.png)


## links of test files
>[testfile2](https://github.com/WEIGUOZENG/markdown-parse/blob/main/test-file2.md)
>
>[testfile3](https://github.com/WEIGUOZENG/markdown-parse/blob/main/test-file3.md)
>
>[testfile4](https://github.com/WEIGUOZENG/markdown-parse/blob/main/test-file4.md)


## syptoms
![image](output2.png)

![image](output4.png)

![image](output1.png)

the output should be all links in testfiles instead of only the first line.



The first syptom is because the infinite while loop does not stop when there is no brackets or parenthesis. So that it will be out of memory.

The second syptom is because the loop should break when there is no 
