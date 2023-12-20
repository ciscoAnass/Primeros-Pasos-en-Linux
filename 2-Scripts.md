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

