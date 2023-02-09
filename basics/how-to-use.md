---
description: How do you use dotify?
---

# ❓ How to use

Running this script is so easy. Just run the script with no arguments to start the dashboard:

```
dotify
```

If the repo configuration file, `~/.config/dotify.repo`, is not generated yet, it'll present you the prompt where you can enter your own dotfiles repository URL. This URL is going to be printed to the file.

If you don't have an existing repository, you can create one. GitHub and GitLab let you create your free Git repository.

## Dashboard

<figure><img src="../.gitbook/assets/master.png" alt=""><figcaption></figcaption></figure>

The script starts with the option chooser to let you select between these options:

* Compare between local dotfiles in your home directory and remote dotfiles repository
  * Option number **1**
  * You can also perform this operation on hidden folders using option number **8**.
* Push all the changes made locally to your remote dotfiles repository
  * Option number **2**
  * You can also perform this operation on hidden folders using option number **13**.
* Pull all the changes from your dotfiles repository
  * Option number **3**
* List all the local dotfiles (home directory)
  * Option number **4**
  * You can also perform this operation on hidden folders using option number **9**.
* List all the remote dotfiles (home directory)
  * Option number **5**
  * You can also perform this operation on hidden folders using option number **10**.
* Copies all the local dotfiles from your home directory to the remote cloned repository
  * Option number **6**
  * You can also perform this operation on hidden folders using option number **11**.
* Copies all the remote dotfiles to the home directory
  * Option number **7**
  * You can also perform this operation on hidden folders using option number **12**.

To exit the program, you can use the **q** option.
