# Introduction to Vi and Vim

### Use case of using text editor in CLI
- Small modifications can be faster, especially when you are currently working in the CLI
- Faster to create and edit at the same time
- Supports multiple format
- When working on a remote server
- Git CLI - Writing Git Commit Message
- Display Kubernetes Configuration Files
- Quickly editing one line or a character in the file

### Install
```
$ sudo apt install vim
```

### Open File
```
$ vim FILENAME.txt
```

### Modes
- Command Mode:
  -  This is the default mode
  -  You cant edit the text
  -  Whatever you type is interpreted as a command
  -  Navigate, search, delete, undo, etc
- Insert Mode:
  - Edit mode
  - Allows you to enter text
