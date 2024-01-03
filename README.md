![image](https://github.com/Nickklein13/CreatingVM-andSoftware/assets/150096883/bb9269c9-9837-4bf1-aa90-52197f1b1ad4)


<h1>Creating , accessing, and setting up software on a VM in Azure</h1>
This project will teach the user how to create a VM on Azure, how to access the VM via remote connection, and how to use one website to create a "non-prompting" download and install of up to 20+ software programs in one click. <br />


This project not only intends to show the user how to access a created VM, but help the user save a ton of time tracking down different software downloads, when it can be done on one communal website. <br />


<h2>Environments and Technologies Used</h2>


- Microsoft Azure

- Virtual Machines

- Ninite.com 


<h2>Operating Systems Used </h2>

- Windows 10 

<h2>Necessary Prerequisites for procedure</h2>

- Access to the internet
- Microsoft Azure subscription

<h2>Procedural Steps</h2>


<p>
1.)   Start off by logging into your Microsoft Azure portal (https://azure.microsoft.com/en-us/). Once in you're going to create a resource group with whatever name will help you remember it. In this example we'll be using RG1 as the name. Use whichever region you prefer.

</p>
<br />

![image](https://github.com/Nickklein13/CreatingVM-andSoftware/assets/150096883/fe421836-44a5-4fca-9d69-4c292e0f6ff2)


<p>
2.) Once a resource group is created, next you'll want to create a Virtual Machine using that group. Go back to the home screen on azure, and search for Virtual Machines tab, using searchbar or howevere you like. Once at the below screen, select to create a virtual machine.
</p>
<br />

![image](https://github.com/Nickklein13/CreatingVM-andSoftware/assets/150096883/ff797c4e-53ef-4f2d-952d-085a47818bc6)




<p>
3.)  When inserting information for the VM, you'll want to select information based on what you're using the project for and whats needed. In this case this we don't need anything crazy, I've posted below what I chose and you can copy exactly to finish this project.  
The important parts you need to keep in mind are;

a.) Selecting your previously made Resource Group ast he RG for this VM
	

  b.) Pay specific attention to your reigon selected.
	

  c.) Enable a "size" you feel is appropriate for whats needed.
	

  d.) Create and JOT DOWN the username and password for the VM. 


Confirm the liscensing agreement, and you shouldn't specifically have to get too advanced so just go ahead and review + create, and once validation has passed, hit create again.


<br />

![image](https://github.com/Nickklein13/CreatingVM-andSoftware/assets/150096883/03ffcb0d-8b30-443d-a712-bacf81f9676e)

<p>
At this point, feel free to take a short break. Deploying a VM could take 2+ minutes. 

4.) Once the VM is created, we're gonna navigate back to the home section of azure. Click on now created VM, and go to overview. Once the information is up, we will note down the PUBLIC IP ADDRESS.

</p>
<br />

![image](https://github.com/Nickklein13/CreatingVM-andSoftware/assets/150096883/74daa6fe-ec23-45a0-8a36-a90909c1bdca)



<p>
Now on our computer we're going to want to go to Start > Remote Desktop connection which will bring you to a window like below. Insert the public IP of your VM, login using your credentials, if there's a prompt about certificate / security say "Yes", and you should be prompted top sign into your VM as it boots up!
</p>
<br />

![image](https://github.com/Nickklein13/CreatingVM-andSoftware/assets/150096883/b3c92b21-b1fa-47db-abf7-14ed5da8070d)
![image](https://github.com/Nickklein13/CreatingVM-andSoftware/assets/150096883/804a0659-69c9-4f85-aded-5e36ada37f30)



<p>
 If this is your first time using a VM, the easiest way to make sense of it, is what it literally is, a second virtual computer running on your current computer booting up with a fresh install of Windows.
</p>
<br />



<p>
5.) Next we'll use Ninite.com to do a quick install of some programs we want. Ninite.com is a very useful website, it helps bypass alot of prompts and download programs in one large heap, and as you're about to see there's everything from discord, steam, java, python, malwarebytes, google drive, etc. 

Open edge, naviate to Ninite.com and select the programs you want to download.

For this project we'll download discord, teamviewer, steam, Opera, chrome and malwarebytes. Then we'll want scroll down, click "Get your ninite" which will simply start the download process, then you can just sit back and let the downloader do its work.
 


<br />

![image](https://github.com/Nickklein13/CreatingVM-andSoftware/assets/150096883/d6c8672b-b6e4-419c-87d0-2dd0d2685873)
![image](https://github.com/Nickklein13/CreatingVM-andSoftware/assets/150096883/91cbe657-ffbd-4eec-9202-33fe013ea229)




<p>
Once done, we'll see these programs have now be succesfully downloaded to the VM, and we are good to move forward!
</p>
<br />




<p>
 Once complete, we now have our VM setup with the software we had set out to download
With that said, this project is now completed with everything it set out to do. We can close the VM, and delete the Resource Group and VM on Azure.

After doing this project, users should now have a much better grasp on how to launch a VM via Azure for whatever purposes they'll need it for, and they'll have a better understanding on how to use a website like ninite to help quick softward downloads to help save time.

</p>
<br />


