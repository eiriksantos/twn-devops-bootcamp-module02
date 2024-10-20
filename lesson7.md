# Introduction to Package Manager

**Software Package** is a compressed archive that contains all the required files for software to run. But take note that most software/applications have dependencies.

**Package Manager:**
- Downloads, installs, or updates existing software from a repository.
- Ensures the integrity and authenticity of the package.
- Manages and resolves all required dependencies.
- Knows where to put all the files in the Linux file system.
- Easy upgrading of software.

### Cheatsheet
```
$ apt

# Search for software packages
$ apt search PACKAGE_NAME

# Remove software package
$ apt remove PACKAGE_NAME

# Refresh the cache
$ apt upgrade

# Location of repositories
$ cat /etc/apt/sources.list

# Add repositories
# PPA = Personal Package Archive
# 
$ add-apt-repository REPOSITORY
```

**Ubuntu Software Center**

**Snap Package Manager**
```
$ snap

# 
$ snap install --classic code
```
