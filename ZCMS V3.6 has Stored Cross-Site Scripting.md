# ZCMS V3.6 has Stored Cross-Site Scripting

## vendors

https://demo.zving.com/demo/login.html

## Vulnerability function

Avatar upload And template include.

ZCMS V3.6.0  has a Stored Cross-Site Scripting vulnerability in Creating an article function, which needs to be authenticated.

## POC

1. login in the System.

username:demo

password:demodemo



2.Find the Creating an article function

![image](https://github.com/user-attachments/assets/62c9eb14-612d-440c-92c7-f8bc91419f2c)



payload:



![image](https://github.com/user-attachments/assets/e23acb7e-3573-4472-b06d-64574e2f8335)

And you can preview








Then find the target url

![image-20250320163742848](https://github.com/user-attachments/assets/1f7be44a-d8ed-4e33-8d3f-b53c8771baf7)

