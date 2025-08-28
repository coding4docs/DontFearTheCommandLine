# Command Line Basics - Coding4Docs

## Just Enough bash To Be Dangerous


### File System Navigation
The `pwd` command stands for "Print Working Directory" which shows the full path to the current directory.

```bash
  pwd
```

The `ls` command lists the files and dirctories in the current directory.

```bash
  ls
```
By using `ls -l` you show a longer version of the directory's contents, including the file or directory's permissions, user and group, file size and date and time created.

```bash
  ls -l
```
You show the directory's hidden files (these start with a dot), with `ls -a`. Many configuration files are hidden this way.

```bash
  ls -a
```

You can use more than one flag with a given command. For example, if you want to see more info and view hidden files, you can use `ls -l -a` or shorten it to `ls -la`.

```bash
  ls -la
```

The `mkdir` command stands for "make dirctory" and creates a directory.

```bash
  mkdir <DIRECTORY_NAME>
```

The `cd` command stands for "change directory" and changes your current directory to a different directory.

```bash
  cd <DIRECTORY_PATH>
```
The `cd ~` or just the `cd ` command takes you to your home directory.

```bash
  cd ~
```
The `cd -`  command takes you to the last directory you were using.

```bash
  cd -
```
The `cd ..`  command takes you up one directory in the directory path.

```bash
  cd ..
```

The `clear` command clears the terminal window. Scrolling up will show the text you had just cleared, by the way.

```bash
  cd ..
```
### Keyboard Commands for Terminal Navigation

Here are a few keyboard commands that I find helpful:

- `Up Arrow`: Shows the last command. Keep pressing the key to show your earlier commands. This is a real time saver!
- `Down Arrow`: Shows the next command.
- `Tab`: Will auto-complete your command. If there is more than one choice, this will display them.
- `Ctrl + L`: Clears the screen, just like the `clear` command.
- `Ctrl + C`: Will cancel a command. This will get you out of a command that keeps running.
- `Ctrl + D`: Exits the terminal.

### A few bonus commands
#### The `whoami` Command

The `whoami` command shows you the current user that you are logged in as. This may be useful when dealing with various remote serves.

```bash
  whoami
```

#### The `date` Command

Believe it or not, the `date` command, shows the current date and time. Also helpful with remote serves in different time zones.

```bash
  date
```

Copyright 2025 Softcode Sytems, LLC> All rights reserved.
