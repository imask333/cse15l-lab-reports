*Installing Visual Studio Code, log in client, runnining commands on client, moving files over SSH, setting an SSH key, and optimizing remote running *
# Installing VScode 

. I had VSCode before, but I went on the VSCode website and downloaded it, and the website is https://www.github.com 
. It took 5 minutes to download
![Installing VScode](https://user-images.githubusercontent.com/114331111/193392523-c9a20985-0d73-4997-be19-6d2c68819397.jpg)


# Remotely connecting

.On the top right of VSCode, I clicked "Command" then "new terminal"
. Then I type cs15lfa22kf@ieng6.ucsd.edu into the terminal to connect to the server. I already changed the key and don't know how to change it to enter password again. 
![remotely connecting](https://user-images.githubusercontent.com/114331111/195960888-c999966d-000f-4c89-afcf-4bd420e694c2.png)


# Trying some commands

. After gettting into the server, I typed in the terminal ls -a, cd, cp, and cat
.I don't know what the cp /home/linux/ieng6/cs15lfa22/public/hello.txt ~/ does.
![Trying some commands](https://user-images.githubusercontent.com/114331111/195961224-a1a39d05-2354-48db-a7eb-f46c71d6b921.png)
 

I compiled and run WhereAmI using javac and java


# Moving files with scp

![Moving files with scp(1)](https://user-images.githubusercontent.com/114331111/193387845-811fdd80-1362-41c7-ba33-16a7f595ece8.jpg)

I copied WhereAmI.javac from client to the server
![Moving files with scp](https://user-images.githubusercontent.com/114331111/193388088-8068fe49-11d1-4834-9b6a-175d496ecc84.jpg)

I logged into the server again and compile WhereAmI and see if server already has WhereAmI from client
![Moving files with scp(3)](https://user-images.githubusercontent.com/114331111/193388390-0f7f519a-356a-4f19-be40-18893a4f102b.jpg)

# Setting an SSH key

.I wrote ssh-keygen in terminal 
![Setting an SSH Key](https://user-images.githubusercontent.com/114331111/193389108-fec54e27-de46-4865-a9d4-d9c7846e8995.jpg)

. I wrote ssh-add because I have a Windows
![setting an ssh key(2)](https://user-images.githubusercontent.com/114331111/193389126-494a12da-b7ac-4945-aa5f-9ad534b3a37a.jpg)

I already logged into ssh and wrote down "mkdir.ssh" and scp Users, but whenever I ssh or scp, it asks for my catchpharase itstead of my password
![setting an ssh key(3)](https://user-images.githubusercontent.com/114331111/193389142-5316ed68-4e41-4b38-ad8b-f4b8fcb4d7f3.jpg)

# Optimized remote running
I copied WhereAmI to server, then I logged into the server, and then I compile WhereAmI in it. It's faster and easier to read than writing each of them on seperate lines. 
![optimized remote running](https://user-images.githubusercontent.com/114331111/193389653-939fa123-1168-470f-be0f-2ba399c08916.jpg)
