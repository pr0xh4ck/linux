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
> Gather Information about your linux machine
```
cat /etc/os-release

lsb_release -a

hostnamectl

uname -a 

uname -r 
```















---























### advanced


### get-powerful-cli
- [ohmyzsh](https://github.com/ohmyzsh/ohmyzsh) - get powerful command line
- [.tmux](https://github.com/gpakosz/.tmux) - get powerful command line




----
### golang

- [Download](https://golang.org/dl/) - Download from official golang website 

or

```bash
sudo wget https://golang.org/dl/go1.17.1.linux-amd64.tar.gz
```

- Now remove your old golang
```bash
sudo rm -rf /usr/local/go/
```

- Now extract your new golang
```bash
sudo tar -C /usr/local -xzf go1.17.1.linux-amd64.tar.gz
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

- Define $PATH
```bash
PATH=$PATH:$GOROOT/bin/:$GOPATH/bin
```
or

```bash
echo "PATH=$PATH:$GOROOT/bin/:$GOPATH/bin" >> ~/.bashrc
```

- If you face any error
```bash
mkdir -p ~/go
```
then 

```bash
echo "PATH=$PATH:$GOROOT/bin/:$GOPATH/bin" >> ~/.bashrc
```
after that 

```bash
tail ~/.bashrc
```










----
### bash










-----
### networking

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







