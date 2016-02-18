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
  
### Hello BigData 

  * [33 Brilliant And Free Data Sources For 2016](http://www.forbes.com/sites/bernardmarr/2016/02/12/big-data-35-brilliant-and-free-data-sources-for-2016/#88155ee67961)
  * 


### News 

  * [MIT News](http://news.mit.edu/2016/quantum-approach-big-data-0125?platform=hootsuite)