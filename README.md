# crackme1
https://crackmes.one/crackme/634e7c1233c5d4425e2cd953


![image](https://user-images.githubusercontent.com/112186489/197393415-892811ca-a05a-485a-a0ae-2d865cb732b7.png)

There are several ways to defeat this crackme, one way would be to rebuild the obfuscation in a seperate c++ project and provide the desired username and make it output the correct password. (example below)

![image](https://user-images.githubusercontent.com/112186489/197393480-83efa0f1-34d1-44d4-89e2-5086c3f4d1b3.png)


Another method to bypass this would be to patch the file and remove the for loop which would make the username == password removing the obfuscation or patch the jump statement to force it to success every attempt regardless of the password.


What the code does:
![image](https://user-images.githubusercontent.com/112186489/197394276-8127a70a-af9d-492b-b211-7cc4ea5e22ca.png)

