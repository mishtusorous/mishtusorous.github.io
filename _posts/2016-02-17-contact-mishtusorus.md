---
layout:     post
title:      Contact mishtusorous
date:       2016-02-15 
summary:    Talk to me. 
categories: howto 
---


### mishtusorous    

  * gmail 
  * twitter 
  * stackoverflow

### Create a new ssh key 

```
ssh-keygen -t rsa -b 4096 -C "mishtusorous@gmail.com"
pbcopy < ~/.ssh/id_rsa.pub
```

### Get the github.io 

```

$ mkdir mishtusorous.github.io
$ cd mishtusorous.github.io

$ git config --global user.name "mishtusorous"
$ git config --global user.email "mishtusorous@gmail.com"
$ git clone git@github.com:mishtusorous/mishtusorous.github.io.git .

$ git add --all && git commit -m "new version" && git push 

```
  
