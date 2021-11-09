```pr0xh4ck © 2021```

```Simplified For Hacker```

## Agenda
 
 - [Basic](#basic)
   - [Intro](#intro)
  



 - [Advanced](#advanced)
   - [Get powerful CLI](#get-powerful-cli)
   - [Python setup](#python)
   - [Golang setup](#golang)
   - [Bash](#bash)
   - [Networking](#networking)







---


### basic


### intro
- About your linux machine
```
cat /etc/os-release

lsb_release -a

hostnamectl

uname -a 

uname -r 
```


- Update & Upgrade

```bash
sudo apt-get update
sudo apt-get upgrade 
sudo apt-get dist-upgrade
```










---























### advanced


### get-powerful-cli
- [ohmyzsh](https://github.com/ohmyzsh/ohmyzsh) - get powerful command line
- [.tmux](https://github.com/gpakosz/.tmux) - get powerful command line






### python


- nstall python3
```bash
sudo apt-get install python3.9
```


- install pip3
```bash
sudo apt install python3-pip
```

- Set update python as default 
```bash
sudo update-alternatives --install /usr/bin/python python /usr/bin/python3.9 10
```


- Now create virtualenv
```bash
pip install virtualenv
```

- Now create virtual diretory
```bash
mkdir python-venv
```
- Now go to inside your python-venv directory through terminal
- Start command

```bash
apt-get install python3-venv
```

```bash
python3 -m venv env
```

- Now activation command
```bash
source env/bin/activate
```

- Now check
```bash
python3 

>>> from pwn import *
```

----
### golang

- [Download](https://golang.org/dl/) - Download from official golang website 

or

```bash
sudo wget https://golang.org/dl/go1.17.3.linux-amd64.tar.gz
```

- Now remove your old golang
```bash
sudo rm -rf /usr/local/go/
```

- Now extract your new golang
```bash
sudo tar -C /usr/local -xzf go1.17.3.linux-amd64.tar.gz
```

- Now see your path
```bash
echo $PATH
```

- Go $PATH
```bash
export GOPATH=/home/pr0xh4ck/go
```

or

```bash
echo "export GOPATH=/home/pr0xh4ck/go" >> ~/.bashrc
```

- Go ROOT
```bash
export GOROOT=/usr/local/go
```
or

```bash
echo "export GOROOT=/usr/local/go" >> ~/.bashrc
```

```bash
mkdir -p ~/go
```


- If you face any error

- Define $PATH
```bash
PATH=$PATH:$GOROOT/bin/:$GOPATH/bin
```
or

```bash
echo "PATH=$PATH:$GOROOT/bin/:$GOPATH/bin" >> ~/.bashrc
```

Then 

```bash
echo "PATH=$PATH:$GOROOT/bin/:$GOPATH/bin" >> ~/.bashrc
```
After that 

```bash
tail ~/.bashrc
```
Eventually

```bash
. ~/.bashrc
```







----
### bash

- [Click here](https://github.com/pr0xh4ck/linux/blob/main/Bash.md)








-----
### networking

- [scanner](https://stafwag.github.io/blog/blog/2021/02/28/howto-install-opevas-on-kali/)
```bash
ps aux | grep -i have
sudo apt install openvas
gvm-setup 
sudo gvm-check-setup
sudo gvm-feed-update
sudo gvm-start
sudo gvm-stop
```


> Start your won Apache server 
```
sudo service apache2 start
```


> Stop your won Apache server
```
sudo service apache2 stop
```


> Check open ports
```
netstat -antp
```







