# Finding difference
* I found the tests with different results by using vimdiff between the two results.txt files in my repository and the provided repository
![image](https://user-images.githubusercontent.com/98358643/172038752-6ae46cb0-f89c-4303-9e95-85e1bd998f14.png)

* Test files with different results are
[test-file 1: 22.md](https://github.com/nidhidhamnani/markdown-parser/blob/main/test-files/22.md) &
[test-file 2: 32.md](https://github.com/nidhidhamnani/markdown-parser/blob/main/test-files/32.md)

# Test-file 1
* The provided implementation is wrong and my implementation is correct.
* Actual output:
![image](https://user-images.githubusercontent.com/98358643/172038917-52692e99-f5d5-4d47-b530-b6d387f9c794.png)
* Expected output: []
* For the provided implementation, the output is inncorrect because it returns the content inside the parentheses regardless whether it's an actual link. In order to solve this, we could add an if condition to check whether the link contains "." inside of it.

# Test-file 2
* The provided implementation is wrong and my implementation is correct.
* Actual output:
![image](https://user-images.githubusercontent.com/98358643/172039068-dd97ce32-8633-4127-9d73-8b932a86dd61.png)
* Expected output: []
* For the provided implementation, the output is inncorrect because it returns the content inside the parentheses regardless whether it's an actual link. In order to solve this, we could add an if condition to check whether the link contains "." inside of it.
