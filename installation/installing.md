---
description: How to install?
---

# 📀 Installing

Installing this script is easy. To install it, follow these steps, assuming that you have either `CURL` or `wget` installed on your Linux system:

## Local and System-wide

There are two ways to install this script on your system. If you want to make this script available to all the users on your Linux system, be sure to install it on your home directory like this:

```
$ curl -fsSL https://raw.githubusercontent.com/Aptivi/dotify/main/dotify > $HOME/dotify
$ chmod +x $HOME/dotify
```

If you want to make this script available to all of the users installed, follow these two scripts as root (`sudo`):

```
$ curl -fsSL https://raw.githubusercontent.com/Aptivi/dotify/main/dotify | sudo tee /usr/local/bin/dotify
$ sudo chmod +x /usr/local/bin/dotify
```

If you prefer using wget to install the script, follow these steps:

* For local installs

```
$ wget -O$HOME/dotify https://raw.githubusercontent.com/Aptivi/dotify/main/dotify
$ chmod +x $HOME/dotify
```

* For system-wide installs

```
$ sudo wget -O/usr/local/bin/dotify https://raw.githubusercontent.com/Aptivi/dotify/main/dotify
$ sudo chmod +x /usr/local/bin/dotify
```

{% hint style="warning" %}
For MinGW, WSL, and Git Bash installs, only the local install is supported.
{% endhint %}
