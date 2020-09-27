# NHibernateCore

Sample DotNet Core Mvc Application using NHibernate

## Cloud9 

### Environment

Name: NHibernate

Description: No description provided

Type: EC2

EC2 instance type: t3.small

Memory: 2 GiB

vCPU: 2

Storage: EBS only


### Run configuration

```sh
dotnet run -p NHibernateCore/NHibernateMvc/NHibernateMvc.csproj --urls="http://localhost:8080"
```

### Git

Edit `~/.bashrc` and set git to use `vim` as default `core.editor` instead of `nano`

```sh
git config --global core.editor /usr/bin/vim
```

Insert into `~/.bashrc` before `PS1=...`

```sh
GIT_PS1_SHOWDIRTYSTATE=1
GIT_PS1_SHOWUNTRACKEDFILES=1
GIT_PS1_SHOWSTASHSTATE=1
GIT_PS1_SHOWUPSTREAM="auto verbose"
```

Setup git user

```
git config --global user.name <your name>
git config --global user.email <your@email>
```

Generate ssh key

[Generating a new SSH key and adding it to the ssh-agent](https://docs.github.com/en/free-pro-team@latest/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)

