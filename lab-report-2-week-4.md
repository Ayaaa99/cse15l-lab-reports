# Code Changes in MarkdownParse
1. The original code is unable to take an empty file as input. 
In order to solve this problem, I added an if condition inside to avoid situations when there's no link inside.
Now, the bug is fixed and the code will return null empty list when the input is empty.
* Code changes:
![image](https://user-images.githubusercontent.com/98358643/164999234-f9736c93-4bf8-4026-88d5-b0dd4b8250a3.png)
* Test file:
[breaking-test1](https://github.com/Ayaaa99/markdown-parser/blob/main/breaking-test1.md)
* Symptom：
![image](https://user-images.githubusercontent.com/98358643/164999650-80e5649a-0e36-4d24-a9f6-4fc6a263f0d6.png)

2. The original code cannot differentiate between image and link.
In order to solve this problem, I added an if condition to determine whether "!" appears in front of the link.
Now, the bug is fixed and the code will only return links but not images.
* Code changes:
![image](https://user-images.githubusercontent.com/98358643/164999793-64d7d3e8-7985-4d9e-ab42-6446df0fa75f.png)
* Test file:
[breaking-test2](https://github.com/Ayaaa99/markdown-parser/blob/main/breaking-test2.md)
* Symptom:
![image](https://user-images.githubusercontent.com/98358643/164999947-55afa140-84e9-449e-8a0a-e8914588b431.png)

3. When a correct link is followed by an imcomplete link, the corret link is not returned.
I changed the "return null" to break so that the code could break out of the while loop when encountering wrong link.
Now, the bug is fixed and the file could successfully return the first correct link.
* Code changes:
![image](https://user-images.githubusercontent.com/98358643/164999793-64d7d3e8-7985-4d9e-ab42-6446df0fa75f.png)
* Test file:
[breaking-test3](https://github.com/Ayaaa99/markdown-parser/blob/main/breaking-test3.md)
* Symptom:
![image](https://user-images.githubusercontent.com/98358643/165000397-5ec013bc-8236-4ffd-be33-0fcb37e4cbe5.png)
