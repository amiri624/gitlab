







#












# How to install Gitlab on a Linux server

```bash
$ https://packages.gitlab.com/gitlab/gitlab-ce
```
```bash
$ gitlab-ce-17.3.6-ce.0.el7.x86_64.rpm
```
```bash
sudo dpkg -i  gitlab-ce-17.3.6-ce.0.el7.x86_64.rpm
```
```bash
sudo apt update
sudo apt upgrade -y
```
```bash
sudo apt install -y ca-certificates curl openssh-server tzdata
```
```bash
ls 
vim /etc/gitlab/gitlab.rb
external_url http://192.168.---.--
sudo gitlab-ctl reconfigure
sudo cat /etc/gitlab/initial_root_password
```
