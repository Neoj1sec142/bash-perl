# Bash Notes:
#### To enter the bash shell:
```sh
bash
```
#### **echo cmd:**
```sh
echo "Hello"
```
#### **sleep cmd:**
- stops all proceses for alloted time 
```sh
sleep 5
```
#### *To create new bash script:*
```sh
nano <name>.sh
```
#### *Then start all bash scripts with:*
```sh
#!/bin/bash
```
- this is so the os knows its a bash shell script
#### *After creating a bash script you will need to use:*
```sh
chmod +x <file>.sh
```
- this is to change the permissions of the file to be executeable
#### **read cmd:**
```sh
read ans
```
#### *Access Variables:*
```sh
echo "you typed $ans"
```
- the $ lets the interpreter know that you are accessing a var.
### **To echo into new file:**
```sh
echo "you typed $ans" > temp.txt
```
- Know if the file is not empty this will erase the contents and replace with new echo 
### To echo without overwriting:
```sh
echo "you typed $ans" >> temp.txt
```
### ** cat cmd:**
```sh
cat temp.txt
```