# Virtualization
## Virtualization: Installation and Configuration of Oracle VirtualBox & Kali Linux, and Execution of Linux Commands

# Aim :
To set up a virtualized environment using Oracle VirtualBox, install Kali Linux as a guest OS, and execute fundamental Linux commands.

# 3.a) Installation and Configuration of Oracle VirtualBox
# Aim:
To install and configure Oracle VM VirtualBox.

Pre-requisites:
Machine with Internet access Minimum 4 GB RAM Sufficient storage space

Steps:
Download Oracle VM VirtualBox:

Visit Oracle VirtualBox Official Site Download installer for your OS (Windows/macOS/Linux). Install Oracle VM VirtualBox (Example: Windows):

Launch Installer → Allow Changes → Click Next. Choose Installation Options → Click Next. Accept Network Interface Warning → Click Yes. Click Install. Finish Installation and Launch VirtualBox. Configure VirtualBox:

Open VirtualBox. Click New → Name VM → Select Type (Linux/Windows) and Version. Allocate: Minimum 2 GB RAM Create Virtual Hard Disk (20 GB recommended). Start Virtual Machine and provide ISO to install OS. Result: Thus, Oracle VM VirtualBox was installed successfully.

# 3.b) Installation and Configuration of Kali Linux
Aim:
To install and configure Kali Linux in Oracle VirtualBox.

Pre-requisites:
Oracle VM VirtualBox Installed 4 GB RAM and 20 GB Storage Minimum Kali Linux ISO image

Steps:
Download Kali Linux ISO:

Visit Kali Linux Official Site Download 64-bit ISO (Installer version). Create a New Virtual Machine:

Open VirtualBox → Click New. Name: "Kali Linux" → Type: Linux → Version: Debian (64-bit). Allocate Memory:

Minimum 2 GB RAM (recommended 4 GB). Create Virtual Hard Disk:

Select VDI (VirtualBox Disk Image). Choose Dynamically allocated. Set Disk size to 20 GB or more. Configure ISO Image:

Settings → Storage → Controller: IDE → Empty CD → Choose Disk File → Select Kali Linux ISO. Start Installation:

Boot Virtual Machine → Choose Graphical Install. Set Language, Region, Keyboard. Configure Network → Set Hostname (e.g., kali). Set root password. Disk Partitioning: Use entire disk → All files in one partition. Install System → Install GRUB Bootloader → Finish Installation. Login to Kali Linux:

Use root credentials. (Optional) Install Guest Additions:

Devices → Insert Guest Additions CD Image → Follow steps inside Kali.

# Snapshots:
AWS Account Creation Snapshot

Snapshot 1: Installing Oracle VirtualBox 
<img width="1919" height="999" alt="image" src="https://github.com/user-attachments/assets/7011ef86-d0a1-4c08-ae7a-5d38520ab2c2" />



Snapshot 2: Kali Running in Virtual 
<img width="1603" height="974" alt="image" src="https://github.com/user-attachments/assets/9b51706e-9a75-4da5-9213-430cfcf6a6a5" />


# Result:
Thus, Kali Linux guest OS was installed and configured successfully.

# 3.c) Execution of Linux Commands in Kali
About Linux:
Open-source operating system. Kernel manages communication between hardware and software. Commands are case-sensitive.

## Linux Commands:
# ls Command The ls command is used to display a list of content of a directory.
Syntax:
1.ls 
<img width="714" height="70" alt="image" src="https://github.com/user-attachments/assets/ed50df7b-eb22-4d8c-9c1b-aed552f13f35" />

# pwd Command The pwd command is used to display the location of the current working directory.
Syntax:
pwd

<img width="193" height="67" alt="image" src="https://github.com/user-attachments/assets/d71d6915-80cb-44ac-a079-8e9b421d47be" />

# mkdir Command The mkdir command is used to create a new directory under any directory.
Syntax:
mkdir <directory_name
<img width="364" height="49" alt="image" src="https://github.com/user-attachments/assets/4c1bb451-7042-4894-87de-bfbf9adfa5f5" />

# rmdir Command The rmdir command is used to delete a directory.
Syntax:
rmdir <directory_name>
<img width="364" height="49" alt="image" src="https://github.com/user-attachments/assets/3d66e7ae-23bb-41da-a8f8-14b3d688758b" />

# cd Command The cd command is used to change the current directory
Syntax:
cd <directory_name>
<img width="223" height="42" alt="image" src="https://github.com/user-attachments/assets/ead5897c-7eb7-42fa-9107-5d975e96a6db" />

# cat Command The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content ofthe file, copy the content of one file to another file, and more.
Syntax:
cat [options] [file_name]
<img width="632" height="73" alt="image" src="https://github.com/user-attachments/assets/8dd75972-5eb8-47bd-80aa-49e1582e0fb2" />
<img width="866" height="71" alt="image" src="https://github.com/user-attachments/assets/f42de012-9529-4deb-a6ea-5bb38f79164b" />


# cp Command The cp command is used to copy a file or directory.
Syntax:
cp [source] [destination]
<img width="300" height="52" alt="image" src="https://github.com/user-attachments/assets/2d7aa6f2-eaea-4cf2-ac89-cf3a301643e7" />
<img width="831" height="62" alt="image" src="https://github.com/user-attachments/assets/81b34869-028a-4ade-8202-ec3e80e1fae3" />



# 8.mv Command The mv command is used to move a file or a directory form one location to another location.

Syntax:
mv [source] [destination]
<img width="293" height="52" alt="image" src="https://github.com/user-attachments/assets/d61c98c0-fbce-4573-9589-a4b8e476c97b" />
<img width="339" height="64" alt="image" src="https://github.com/user-attachments/assets/021e5a4a-176b-4d70-abe4-044a2420fb1d" />


# touch Command Create empty file.
Syntax:
touch [filename]
<img width="185" height="44" alt="image" src="https://github.com/user-attachments/assets/fe319443-170a-4285-bc76-3a946863d4ae" />

# vi Command Edit file contents using editor.

Syntax:
vi [filename]
<img width="192" height="51" alt="image" src="https://github.com/user-attachments/assets/3c851699-ebfd-4bd7-b9de-fb54b4114109" />


Result:
Thus, various Linux commands were executed successfully in Kali Linux virtual machine.
