#POSHMARKS


An implementation of [bashmarks](https://github.com/huyng/bashmarks "bashmarks") for Powershell

##Commands

```
s <bookmark_name> - Saves the current directory as "bookmark_name"
g <bookmark_name> - Goes (cd) to the directory associated with "bookmark_name"
p <bookmark_name> - Prints the directory associated with "bookmark_name"
d <bookmark_name> - Deletes the bookmark
l                 - Lists all available bookmarks
```

##Sample Usage

```bash
cd C:\users\manoj\Desktop
s desktop
cd C:\users\manoj
s home
g desktop
l
```
