+++
date = '2024-11-22T20:58:18-07:00'
draft = true
title = 'How to use Hugo to build a personal blog on mac'
+++

### Introduction
If you are a complete computer novice and want to build a personal blog on mac, you can try this 
instructions.

<br>

# Install
### Software Installation
First, we install ITerm and VScode(Visual Studio Code) on the computer. You can both find their 
installing packages on the internet.

Then, open ITerm, copy this into it:
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
![install hugo](static/images/install-hugo-link.png)
Next, just follow the instructions by iTerm, entering your computer password.
It will be something like this:
```
(base) computer@apple ~ % /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
==> Checking for `sudo` access (which may request your password)...
Password:
==> This script will install:
```
After installing successfully, input `hugo version` to check
```
(base) xiaoyao@000 ~ % hugo version
hugo v0.139.0+extended+withdeploy darwin/arm64 BuildDate=2024-11-18T16:17:45Z VendorInfo=brew
```

### Select the file location
See what files are in your computer:
```
ls
```
![ls to find directory](/static/images/ls-to-find-directory.png)

Select one to install it:
```
cd Documents
```
(You can do more steps if needed.)

Then make new directory:
```
mkdir hugo
```
(You can use any other names if you want!)

Get in to the file we have just made:
```
cd hugo
```

Create your own blog!!
```
hugo new site tan270
```
![hugo new site tan270](/static/images/hugo-new-site-tan270.png)

# Construct
### Basic Framework
Then,
```
tree
```
We can see all files created by default:
![Tree for the file](/static/images/tree-for-hugo.png)


▲ If there's no tree on your computer, like this:
![No tree on your computer](/static/images/no-tree.png)
  Just install it,
![install tree](/static/images/install-tree.png)