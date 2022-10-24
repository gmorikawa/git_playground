# GitPlayground

## Overview
This is a repository for practicing Git and GitHub functionalities.

## Basics
Git is already a complex 

### Initialize a directory as a git repository
On terminal, execute the following command to start a directory as a git repository. If __no directory__ is given as parameter the current directory is used by default.

```
$~ git init <path>
```

### Configuring Git variables
Every git commit is signed with a username and email. To define this values use the following commands:

```
$~ git config --global user.name "username"
$~ git config --global user.email "username@mail.com"
```

Note that the _--global_ flag was used in this command. 