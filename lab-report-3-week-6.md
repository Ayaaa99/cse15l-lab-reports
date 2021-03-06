# Streamlining ssh Configuration
* Include hostname and username for different servers into .ssh/config file.
![image](https://user-images.githubusercontent.com/98358643/167335586-f7e26bb1-e67c-47fc-af37-46ef254084b4.png)
* Log in into ieng6 server using ssh ieng6.
![image](https://user-images.githubusercontent.com/98358643/167335685-c1731a78-7796-4760-a6cc-bb4e92297d80.png)
* Copy a file from local computer to the ieng6 server through scp command using config file.
![image](https://user-images.githubusercontent.com/98358643/167337223-03276b44-698f-45f2-ac6b-349ff4088a9f.png)


# Setup Github Access from ieng6
* Create rsa key and store the public key in Github account.
![image](https://user-images.githubusercontent.com/98358643/167345303-54cf2677-2ef8-483c-b2e0-8ce5097b702a.png)
* Check the private key stored in ieng6 user account.
![image](https://user-images.githubusercontent.com/98358643/167345404-e14ea808-7482-492a-97bc-eeead7ad0667.png)
* Make changes to file in markdown-parser on ieng6 account and push changes to github
![image](https://user-images.githubusercontent.com/98358643/168658743-db1d9387-8d60-459e-ad30-644e0df82178.png)
* [Link to the commit message](https://github.com/Ayaaa99/markdown-parser/commit/bef392147bde02ecf0bdfc6eadd535b09c38e2b3)


# Copy the whole directory into ieng6
* Use scp to copy the markdown-parser directory into ieng6 account
![image](https://user-images.githubusercontent.com/98358643/168448572-88f1baf4-9612-483f-969d-88a7a815c050.png)
* Log in into ieng6 account and compile and run markdown-parser codes
![image](https://user-images.githubusercontent.com/98358643/168461490-76df03c7-9a06-421c-8b07-3ff8f6906c71.png)
* Copy the directory to ieng6 account and compile and run test remotely on local computer.
![image](https://user-images.githubusercontent.com/98358643/168658092-2e8dd3fd-2ced-4d94-89e8-549ba1cd8ae8.png)

