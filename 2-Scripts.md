  # Scripts


First let's talk about some rules that we have to respect :

1-**#!/bin/bash** : we should always put it in every first line of a script file

2-**.sh** : The script file should always done with **.sh**

3-To execute the Script file we use this command : 
>sh fichero1.sh


***
## Let's create our first basic Script

<img title="script1" alt="script" src="/img/script1.png">

- We can see in the picture that we did create a script file and we did put **#!/bin/bash** int eh first line and in the second line i put a comment (author) of the file which is optional , u can put it or no and finally we did put **echo "Hello world"** which mean print hello word so when we execute the script , we get Hello World as the result of execution .

<img title="script1" alt="script" src="/img/execscript.png">
  
- If we want to skip the line in the text so we do use **\n** ( it's look like <br> in html )

<img title="script1" alt="script" src="/img/skipline.png">

***
# Values

<img title="script1" alt="script" src="/img/allvalues.png">

- TO crate a value we should respect this syntax 'Keyword' = 'Value'

  for example

  > nota=10
  >
  > echo " has sacado $nota "


- SO when we execute the script , the result gonna be **Has sacado 10** because $nota did take the value of 10 before
- 
***
- As well we have a great tool on Scripting which is **read -p** , this tool is usable for the the automation of changeble value
  
- For example : in  company we have more than 40 users ( workers ) and every worker have a different name , and we want to create a script that every time they log-in the script say **( Hello #User , have good day)** , so to do that we dont have to create a 40 script and every script with a user name becuase **read -p** gonna help us

- So we just gonna put

  > read -p " What is your username " username
  > 
  >echo "Hello $username , have a good day"


  so basicly we just ask the user about his username and when he put his username , the script automate the answer to ( hello $username , have a good day ) wich make every worker name automated by answering with his name
<img title="script1" alt="script" src="/img/readp.png">

<img title="script1" alt="script" src="/img/valuesresult.png">

***
# Passwords


<img title="scriptpass" alt="script" src="/img/scriptpass.png">

<img title="scriptpass" alt="script" src="/img/scriptpass.png">

