# CONNECT TO VAGRANT HOST W/O vagrant ssh

```commandline
vagrant ssh-config > vagrant-ssh
ssh -F vagrant-ssh rundeckserver01.laptop.local
```