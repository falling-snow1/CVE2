# DedeCMS V5.7.92-V5.7.116 has Stored Cross-Site Scripting

## vendors

https://www.dedecms.com/

## Vulnerability function

Avatar upload And template include.

DedeCMS V5.7.92 and later has a Stored Cross-Site Scripting vulnerability in voting function, which needs to be authenticated.

## POC

1. login in the System.

username:admin

password:admin

Any user who can operate the voting function can do so

2.Find the voting function

![image-20250320163420575](C:\Users\CPZX-001\AppData\Roaming\Typora\typora-user-images\image-20250320163420575.png)

payload:



![image-20250320163630386](C:\Users\CPZX-001\AppData\Roaming\Typora\typora-user-images\image-20250320163630386.png)

Here you can set up voting for users who are not logged in





Then find the target url

![image-20250320163742848](C:\Users\CPZX-001\AppData\Roaming\Typora\typora-user-images\image-20250320163742848.png)
