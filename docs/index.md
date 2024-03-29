# Introduction

Welcome to the **Red Hat Gluster Storage Hands-on Test Drive**. To make your Gluster experience awesome, the contents of this test drive have been divided into the following modules.

- <a href="gluster-module-1/">**Module 1 :** Introduction to Gluster concepts</a>
- <a href="gluster-module-2/">**Module 2 :** Volume Setup and Client Access</a>
- <a href="gluster-module-3/">**Module 3 :** Volume Operations and Administration</a>

## What is Gluster?

Gluster provides open, software-defined file storage that scales out as much as you need. You can easily and securely manage large, unstructured, and semi-structured data at a fraction of the cost of traditional, monolithic storage. And only Red Hat lets you deploy the same storage on premise; in private, public, or hybrid clouds; and in Linux® containers. You can read more about gluster here: <https://www.redhat.com/en/technologies/storage/gluster>

## About the Test Drive

The **Red Hat Gluster Storage** Hands-on Test Drive is designed in a progressive modular format. Newcomers to Gluster will generally have the best experience by following the modules and steps in order. To faciliate skipping modules or resuming progress at a later date, the modules are also designed to be independent and not reliant on the activities of any preceeding module.

While the guided lab processes is designed to offer a progressive educational experience, you are also encouraged to use the lab in a free-form manner to explore Gluster and its features. For your convenience, a reference of the lab resources is provided below.

### Lab Resources

| Lab Node  | Internal IP Address | Function               |
|-----------|---------------------|------------------------|
| rhgs1     | 10.100.1.11         | Local Gluster server 1 |
| rhgs2     | 10.100.1.12         | Local Gluster server 2 |
| rhgs3     | 10.100.1.13         | Local Gluster server 3 |
| rhgs4     | 10.100.1.14         | Local Gluster server 4 |
| rhgs5     | 10.100.1.15         | Local Gluster server 5 |
| rhgs6     | 10.100.1.16         | Local Gluster server 6 |
| client1   | 10.100.1.101        | RHEL client 1          |
| client2   | 10.100.1.102        | RHEL client 2          |
| winclient | 10.100.1.103        | Windows client         |

## Test Drive Prerequisites

### SSH and RDP
If you are a Windows user, you will need a Secure Shell client like *PuTTY* to connect to your instance. If you do not have it already, you can download the PuTTY client here: <http://the.earth.li/~sgtatham/putty/latest/x86/putty.exe>

Mac and Linux users, you will use your preferred terminal application (this should already be installed on your machine). For accessing the Windows lab client system interface via RDP, you will need a RDP client program such as *Vinagre* on Linux or the *Microsoft Remote Desktop* client for Mac. Vinagre is likely available for your Linux distribution using your standard package manager. You can download the Mac RDP client here: <https://www.microsoft.com/en-us/download/details.aspx?id=18140>

## Getting to Know Your Lab Environment

### Starting the Lab

> **NOTE** Module 1 is not hands-on and does not require the lab to be started. Because the time limit will begin after clicking the **Start Lab** button, you may wish to wait until you are ready to begin a later module before you click the button.

1. On the **Lab Details** tab to the right, notice the lab properties:

   ![](http://us-west-2-aws-training.s3.amazonaws.com/awsu-spl/spl02-working-ebs/media/image004.png)

   - **Setup Time -** The estimated time for the lab to start your instance so you can access the lab environment.
   - **Duration -** The estimated time the lab should take to complete.
   - **Access -** The time the lab will run before automatically shutting down.

<ol start="2"><li>Click the <img src="http://us-west-2-aws-training.s3.amazonaws.com/awsu-spl/spl02-working-ebs/media/image005.png"> button in the navigation bar above to launch your lab. If you are prompted for a token, use the one distributed to you (or credits you've purchased).</li></ol>

> **NOTE** It may take **up to 10 minutes** for your lab systems to start up before you can access them.

   A status bar will then show the progress of the lab environment creation process. Your lab resources may not be fully available until the process is complete.

   ![](http://us-west-2-aws-training.s3.amazonaws.com/awsu-spl/spl02-working-ebs/media/image006.png)

<ol start="3"><li>The <strong>Connect</strong> panel to the right is automatically opened when the lab starts. Practice closing and re-opening it. While open it may obscure some of these lab instructions temporarily.</li></ol>

> **TIP** If the **Connect** tab is unavailable, make sure you have clicked **Start Lab** at the top of your screen.


## Accessing the lab

All of the information you need to access your test drive lab instances is available via the **Addl. Info** tab to the right. There you will find relevant public IP addresses, usernames, and passwords for your personal lab environment.

> **TIP** If the **Addl. Info** tab is not visible, make sure you have clicked the **Start Lab** button at the top of your screen and that the lab build has completed.

All Linux instances may be accessed via your local SSH client.

All Windows instances may be accessed via your local RDP client. **Windows instances will be logged into with the** ***Administrator*** **username and with the password available in the** ***Addl. Info*** **tab.**
