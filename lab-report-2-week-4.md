# Code Changes in MarkdownParse
1. The original code is unable to take an empty file as input. 
In order to solve this problem, I added an if condition inside to avoid situations when there's no link inside.
Now, the bug is fixed and will return an empty list when the input is empty.
* Code changes:
![image](https://user-images.githubusercontent.com/98358643/164999234-f9736c93-4bf8-4026-88d5-b0dd4b8250a3.png)
* Test file:
[breaking-test](https://github.com/Ayaaa99/markdown-parser/blob/main/breaking-test.md)
* Symptom：
![image](https://user-images.githubusercontent.com/98358643/164999650-80e5649a-0e36-4d24-a9f6-4fc6a263f0d6.png)
