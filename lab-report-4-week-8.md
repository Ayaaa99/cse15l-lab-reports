# Snippet 1
* This markdown snippet should produce the following result:
![image](https://user-images.githubusercontent.com/98358643/169673013-e0c7306f-44cf-493c-9d03-6ca043fc3734.png)
* This is the new test I added to MarkdownParseTest.java to test snippet 1:
![image](https://user-images.githubusercontent.com/98358643/169708251-edd2b952-a9e0-4121-935d-49f386d5e3e8.png)
* This is the error that appear when running the Junit test with the new test added:
![image](https://user-images.githubusercontent.com/98358643/169708221-d7ad9eb5-d44d-469c-90b5-14c1c31fd5f6.png)
* In order to solve the problem that the "url.com" is incorrectly included, I can add an if statement to the code, and skip to the next link if a "`" sign is found in front of the open bracket. Next, to make the ucsd link to be included, I should change the if condition for finding "](". Instead of checking whether the next character following "]" is "(", I should change it to checking whether the character in front of "(" is a "]". In this way, the code could correctly add the link to the list even if there's "]" inside the "[]".


# Snippet 2
* This markdown snippet should produce the following result:
![image](https://user-images.githubusercontent.com/98358643/169710105-52c9b186-615b-4937-baf6-32406a951542.png)
* This is the new test I added to MarkdownParseTest.java to test snippet 2:
![image](https://user-images.githubusercontent.com/98358643/169710294-88f6227f-fd64-4a03-9707-7545f102b8a4.png)
* This is the error that appear when running the Junit test with the new test added:
![image](https://user-images.githubusercontent.com/98358643/169710331-b4bf37d8-a24c-48c8-a717-8f2e731e0a33.png)

