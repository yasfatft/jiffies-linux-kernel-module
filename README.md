# linux Kernal Module
here are 2 LKM that was implemented by myself. 
## 1. jiffies module 
this module can be loaded to the linux kernal and work also as a linux proccess. after loading the module into kernel if you call the proccess it shows the number of interrups that had been occured into the CPU since start-up of the system!
## 2. seounds module
this is basically like the first one but a little different in runtime,when you call the proccess it show the time(int secounds) since the module was loaded into the kernel 
## how to use 
you have to run below command to execute file Makefile:
```
make
```
if it run correctly then you can see filename.ko beside the main C file (filename.c (like jiffies.c)) and some other files. 
then you have to load module to the kernel by:
```
sudo insmod filename.ko
```
it's important to use the correct format (.ko not .c).
then it's possible to see what will be happen when you call the proccess by:
```
cat /proc/Filename  
``` 
 like cat /proc/seconds
 ## how to reach me
 if you wanna to talk to me about anything! like suggestions, problems, ideas or... use one of bellow ways:
- Email: yasfatft@gmail.com
- Telegram Acount: @yasfatft
- Linkedin: linkedin.com/in/yasin-f-b7624210b
