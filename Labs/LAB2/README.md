# Lab 2 | Command Line
## George Redfern
### Lab Instructions:
Go to the IOT repository. Review Lessons 1 and 2. Then, open a terminal and enter the following commands:</br>
`hostname`, 
`env`, 
`ps`, 
`pwd`, 
`git clone https://github.com/kevinwlu/iot.git`, 
`cd iot`, 
`ls`, 
`cd`, 
`df`, 
`mkdir demo`, 
`cd demo `, 
`nano file`, 
`cat file`, 
`cp file file1`, 
`mv file file2`, 
`rm file2`, 
`clear`, 
`man uname`, 
`uname -a`, 
`ifconfig`, 
`ping localhost`, 
`netstat`. 
Document results to GitHub repository.

---
### hostname: displays the computer's network host name
---
![image](https://github.com/user-attachments/assets/3a06c450-f048-478e-b97b-ef119e8a320d)
---

---
### env: displays the computer's environment variables (had to include gci with windows)
---
![image](https://github.com/user-attachments/assets/ce7f16fd-86e2-4f92-b038-2208debf673f)
![image](https://github.com/user-attachments/assets/97cc1cb8-e5f3-4929-85ab-522ead0c135a)
---

---
### ps: gives info about running processes on the computer
---
![image](https://github.com/user-attachments/assets/89772bcb-0c40-44f0-9f4a-ffdebc826c79)
![image](https://github.com/user-attachments/assets/d5bea228-287b-4b66-b683-e22e22b43ecd)
![image](https://github.com/user-attachments/assets/90079c0a-611b-4582-ac85-60941867ffda)
![image](https://github.com/user-attachments/assets/cb2cb3cc-e558-4383-a7d5-4ed850999c72)
![image](https://github.com/user-attachments/assets/f9cbeca8-4b70-4445-9d7e-c73dd7b68074)
![image](https://github.com/user-attachments/assets/f55b4cf5-e6a9-4ed4-93cb-b32904a5bafe)
![image](https://github.com/user-attachments/assets/20c95b6a-5269-44a1-a450-938715791187)
![image](https://github.com/user-attachments/assets/d3850c83-cb31-4e18-8a4f-b9f007aa7b24)
![image](https://github.com/user-attachments/assets/f9a7e6e4-a9aa-415d-beb6-213f06cdaa89)
---

---
### pwd: shows full path of the current directory you are in
---
![image](https://github.com/user-attachments/assets/4feb603e-f770-4bd5-b6be-a2d23c7f4e47)
---

---
### git clone https://github.com/kevinwlu/iot.git: This command clones the git repository from the given website. Ensure Git is installed for the command to function. In this instance, it clones the IOT repository.
---
![image](https://github.com/user-attachments/assets/f2e2c368-a280-40c8-8397-af0e728de4fe)
---

---
### cd iot: changes the working directory to IOT.
---
![image](https://github.com/user-attachments/assets/bfbb064f-2478-4651-9900-d5872aaaa944)
---

---
### ls: displays a list of all files in the current directory (besides hidden files)
---
![image](https://github.com/user-attachments/assets/87989ec4-cebf-4925-b986-d7b97c6704b3)
---

---
### cd: changes directories to your home directory.
---
![image](https://github.com/user-attachments/assets/61e444da-4e4d-488d-a5db-45613822e933)
---

---
### df: displays disk information about disk space on a file system (Had to use Get-PSDrive because I am in windows)
---
![image](https://github.com/user-attachments/assets/169d1980-ad3e-40f7-9c20-ffb464a9c79a)
---

---
### mkdir demo: makes a new directory called demo
---
![image](https://github.com/user-attachments/assets/2f15b378-c90d-4642-8f2f-8dbfa66cd3cb)
---

---
### cd demo: changes working directory to demo
---
![image](https://github.com/user-attachments/assets/1d580a9e-0ecf-493a-8b68-ebb201596141)
---

---
### nano file: Because a file named 'file' doesn't exist yet, this command will open a blank text editor where you can type to create or edit content. Once you finish and save, it will store your changes in a new file named 'file.'
---
![image](https://github.com/user-attachments/assets/7700251e-5d3c-4f9f-8993-bcf2d2850ad9)
![image](https://github.com/user-attachments/assets/23982b85-7fb4-4500-a117-4104d92479d8)
---

---
### cat file: displays the contents of 'file' (added .txt to prevent error)
---
![image](https://github.com/user-attachments/assets/4d61a20c-0457-4175-9bfd-47ea439e5af3)
---

---
### cp file file1: copies file into file 1 (added .txt to prevent error)
---
![image](https://github.com/user-attachments/assets/ca30695d-7527-4ae6-bc57-39260feb8303)
---

---
### mv file file2: moves(renames) file to file2 (added .txt to prevent error)
---
![image](https://github.com/user-attachments/assets/a7a8207a-a65f-4973-9412-e63cfd8be270)
---

---
### rm file2: removes (deletes) file2
---
![image](https://github.com/user-attachments/assets/a268a5b2-1d84-4f3b-9ed0-45edda260f25)
---

---
### clear: clears all content on the terminal screen
---
![image](https://github.com/user-attachments/assets/12986fa1-f4e8-4f67-a55c-65cd7ff286e0)
---

---
### man uname: opens the manual page for the 'uname' command. Manual pages show documentation about commands. (Had to use Get-Help because I am in windows)
---
![image](https://github.com/user-attachments/assets/f2dab83e-2fec-4392-a050-402a9056cc00)
---

---
### uname -a: odisplays fetialed system info in a single line (only works in GitBash)
---
![image](https://github.com/user-attachments/assets/b3256a0a-73d2-4d4c-92c2-c49dfa4e8b5e)
---

---
### ifconfig: displays a complete list of all network interfaces, including their IP addresses, MAC addresses, and other pertinent details. (Used Get-NetAdapter because I am in windows)
---
![image](https://github.com/user-attachments/assets/e9770b0e-08dc-4e17-af7b-a4a885f31790)

---

---
### ping localhost: sends network packets to your own machine to verify that the network stack is working correctly.
---
![image](https://github.com/user-attachments/assets/4a43a7f5-1890-495b-a46d-6d4a1269cb38)
---

---
### netstat: displays information about your network connections, including active TCP connections, listening ports, routing tables, and network interface statistics.
---
![image](https://github.com/user-attachments/assets/1fefdca9-91d0-4a07-9670-ea63e7c171cf)
---

# Summary
In this lab, I explored a variety of important terminal commands. Through completing the activities, I gained hands-on experience with commands related to viewing system information, managing processes and directories, handling file operations, working with networks, and using GIT for version control. This lab helped me develop a stronger understanding of how to interact with the system through the terminal, and it built a solid foundation for more advanced command-line tasks in the future. Additionally, I have learned that commands differ between windows and linux, thus, I have to be careful with the proper commands to use. 

I pledge my honor that I have abided by the Stevens Honor System- George Redfern
