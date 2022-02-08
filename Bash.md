- [Agenda]()
  - [Intro](#intro)
  - [Compulsory](#Compulsory)
  - [Basic](#basic)
  - []()
  - []()






---
---


### intro

- What is Bash ?
```text
- It is a Unix shell and command language
- It is written by Brian Fox
- It is released in 1989
```






### Compulsory

- grep 
```

```

- cut
```

```

- sort
```

```

- xargs
```

```

- tr
```

```





















----

### basic

- Print something

```bash
#!/bin/bash
# This hash symbol is called comment
# Author Name: pr0xh4ck
# Creation Date: 
# Modification Date: 

echo "Hack The Planet"
# echo use for print your data
```


- Taking Input

```bash
#!/bin/bash

echo "Enter your name: "
echo
read name
echo
echo "Your name is: $name"
echo;
echo "Enter you multiple name"
echo
read name1 name2
echo
echo "Your First name is: $name1"
echo
echo "Your Last name is : $name2"
```

- Chain of Commands

```bash
#!/bin/bash


echo "Now starting your progress"
echo
cd ~/Desktop
mkdir pr0xh4ck
ls
echo
echo "Your progress is END"
```


- if Statement

```bash
#!/bin/bash


echo "your domain 100 "
echo
domain=100
echo
if [ $domain -eq 100 ]
then
echo "It is true"
else
echo "It is false"
echo
echo "done"
fi
```

- if else Statement

```bash
#!/bin/bash



echo "Enter your password"
read password
echo
if [ $password == pr0xh4ck ]
then 
echo "Here you go"
else
echo "Sorry, your password is wrong"
echo
fi
```


- case 

```bash
#!/bin/bash

case "${1}" in
start)
echo "Starting"
;;
stop)
echo "Stoping"
;;
status)
echo "Status"
;;
esac
```

- case 2

```bash
#!/bin/bash

echo "Please enter your option"
echo "Enter a for Name"
echo "Enter b for Roll"
echo "Enter c for Phone"

read input
case ${input} in

a) 
echo "Pr0xh4ck" 
;;
b) 
echo "65,535" 
;;
c) 
echo "+880" 
;;
esac
```



















