# **How to install Ubuntu on VMware Workstation**

Installing a Linux distro is no more a big problem because this blog is here to help you to install the famous Linux distro on VMware workstation.

##### Follow some basic steps to install the Ubuntu x64 bit on VMware workstation.

### Step 1.

##### Pre-requisite:

* VMware workstation should be installed
* Ubuntu ISO disk images should be downloaded.

1. If these are not done you can download VMware workstation from <https://www.vmware.com/products/workstation-player.html> and you can install VMware as a normal software installation.
2. You can download Ubuntu disk image from <https://ubuntu.com/download/desktop>. 

### Step 2.

Now run the VMware workstation and following screen will be shown to you.

![VMware workstation](ubuntu\vmware1.jpg)



### Step 3.

Click on the create new virtual machine and the following screen will be shown to you. Click on browse button and choose the ISO file of ubuntu .

![VMware Workstation](ubuntu\vmware2.jpg)



### Step 3.

Click the next button now.

![VMware Workstation](ubuntu\vmware3.jpg)

### Step 4.

The following screen will be shown to you. Enter the credentials you want to set and click the next button.

![VMware workstation](ubuntu\vmware4.jpg)

### Step 5.

You can give the minimum storage to 20 GB for the sake of installation of ubuntu and you can give as maximum space as you want. you can leave all other options to default selected. Now click on Next.

![VMware Workstation](ubuntu\vmware5.jpg)

### Step 6.

You can keep the default configuration for this but if you want to increase the RAM for your virtual machine you can click on customize hardware and then you can increase the RAM and after this you can close the customize hardware dialogue box. Now Click the finish button.

![VMware Workstation](ubuntu\vmware6.jpg)



### Step 7.

You will se this loading screen after finishing. Duration of visibility may depend on your system.

![VMware Workstation](ubuntu\vmware7.jpg)



### Step 8.

When this screen appears you have to click on install Ubuntu button this button position may vary in different systems but i have it on bottom right corner of screen. 

![VMware Workstation](ubuntu\vmware8.jpg)



### Step 9.

Select the preferred language and click the continue button.

![VMware Workstation](ubuntu\vmware9.jpg)



### Step 10.

Now you have to select the preferred keyboard layout. You can keep it default and then you have to click Continue button.

![VMware Workstation](ubuntu\vmware10.jpg)



### Step 11.

You can choose normal installation as default and if you don,t want to download the updates at the time of installation you can uncheck the Download updates while installing Ubuntu. Now click the continue button.

![VMware Workstation](ubuntu\vmware11.jpg)



### Step 12.

Now click on first option which is already selected as default if it is not selected at your side and click on install now button.

![VMware Workstation](ubuntu\vmware12.jpg)



### Step 13.

You will receive this dialogue box click on continue button.

![VMware Workstation](ubuntu\erase_disk.png)



### Step 14.

Now You have to choose your time zone simply. Select the time zone and click the continue button.

![VMware Workstation](ubuntu\timezone.png)



### Step 15.

You will receive the following screen and now enter your name, computer name and user name and credentials of your own choice. And finally select the continue button.

![VMware Workstation](ubuntu\final.png)



### Step 16.

You will receive the window installing the Ubuntu. Now simply wait for it to complete.

![VMware workstation](ubuntu\installation.png)



### Step 17.

Now after it is completed and the machine is restarted you will got the login screen

![VMware Workstation](ubuntu\cred.png)



Enter you credentials and you are free to go. Ubuntu is installed.

![VMware Workstation](ubuntu\installed.png)



## Running your first C program on Linux

Starting programming in Linux is very easy in Linux . If you want to start writing C++ programs on Linux you just have to write the C++ program and then you have to compile your program using compiler provided in Linux and you,re done. The program is ready for Execution. Follow some basic steps with me.

#### Step1:

Check weather the C++ compiler is installed on Linux by running this command.

```bash
g++ --version
```



It is already installed it will print the version of g++ compiler.

![Vmware](ubuntu\g++version.png)



But if is not installed and giving you error you can install it with following command.

```bash
sudo apt-get install g++
```

But if you also want to install whole GNU/g++ compiler collection you can run following command.

```bash
sudo apt-get install build-essentials
```



Now you are ready to write programs in C++ or C. 

#### Step 2:

You can use different text editors in Linux to write programs but now we are gonna use a console base editor to write our first c++ program which is **nano**. It comes pre-installed in Linux.

Give command nano and filename with it and it will open editor for you

![Vmware Workstation](ubuntu\nano.png) 

![Vmware](ubuntu\c++program.png)



Press **Control+S** to save the program and then **Control+X** to exit the editor.

#### Step 3:

Now you have to compile your written program with g++ compiler 

**Syntax** :

```bash
g++ [filename] -o [output_filename] 
```

It will compile and give you output file

![Vmware](ubuntu\compile.png)



#### Step 4

Now you have to run the program as it is now compiled use ./ and the followed by file name and hit the enter button it will run your file

```bash
./hello
```

![Vmware](ubuntu\run.png)



**Thanks For Reading**
