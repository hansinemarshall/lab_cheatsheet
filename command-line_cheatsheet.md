# **<u>Terminal</u>**

## <u>General commands</u>
### **cd**
cd = *change directory* 

Further examples:
- cd ~ = go to user root
- cd - = go to the directory you were previously working on 
- cd .. = go to parent directory of *pwd*
    - pwd = *present working directory*


### **ls** 
ls = *lists content of directory*

Further examples:

- ls -a = list all, which includes *hidden files*
    - these are files with names starting with a period (.)

### **rm** 
rm = *remove file*

Further examples:
- rm -r = *remove + recursive flag* = removes folder 

### **mkdir**
mkdir = *make new directory*

### **touch**
touch = *create new file*

### **mv**
mv = *move file into new directory* OR *change name of file in same directory*

Further examples:
- mv 'name of file' *insert name of different directory* / = moves the file to a different directory 
- mv 'name of file' 'new file name' = changes the name of the file in the same directory

### **cp**
cp = *copy*

Further examples:
- cp -r = copies entire directory 

### **pbcopy**
pbcopy = *copies to clipboard*

## <u>Commands for editing files</u>
> these are useful commands for Utility Scripts 

### **echo**
echo = *add to file* 

Further examples:
- echo 'text to add' >> *insert name of file* = appends a new line each use 
- echo 'text to add' > *insert name of file* = overrides contents of file 

### **cat**
cat = *read contents of file*

### **open** 
open = *opens TextEdit app*


# <u> Git and GitHub </u>
Git &rarr; version control system

GitHub &rarr; tool for storing and sharing remote repos 

## <u>Useful git commands </u>

### **git clone**
git clone 'SSH key' = *clones remote repo from GitHub*

### **git log**
git log = *shows commit history*
- press Q to exit 

### **git add .**
git add . = *adds all recent changes made to staging area*

### **git commit**
git commit = *commits changes*

Further examples:
- git commit m- 'comment explaining commit' = *commits changes with comment explaining changes made*

### **git push**
git push = *pushes to remote repo*

Further examples:
- git push origin main = *specifies branch*

### **git status**
git status = *shows recent changes and if they are staged for commit*


### **git init**
git init = *initialises empty repository locally*
- NOTE: need to create an empty repo on github

### **git remote add origin ' '***
git remote add origin 'SSH key from empty repo on github' = *adds repo origin*
