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

![image-20250320163420575](https://github.com/user-attachments/assets/4e2ab52c-6590-4790-8a52-a75ea420333e)


payload:



![image-20250320163630386](https://github.com/user-attachments/assets/0a07b3e1-4f64-46a1-8565-eb69b11eb8e3)


Here you can set up voting for users who are not logged in





Then find the target url

![image-20250320163742848](https://github.com/user-attachments/assets/1f7be44a-d8ed-4e33-8d3f-b53c8771baf7)

