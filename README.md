# Home Lab Microsoft Office 365

<h2>Overview: Understanding Office 365 Home lab</h2>

This repository documents my home lab project focused on exploring and understanding Office 365 within a lab environment. The lab covers setting up and configuring Office 365 services, managing user accounts, and exploring key features like calendar management.  As part of the calendar management, the project also covers configuring calendar permissions, delegating access rights, and setting up shared calendars to ensure proper access control. 

<h2>Objectives</h2>

- **Set up and configure Office 365 services** to understand the foundational components of a cloud-based productivity environment.
- **Manage user accounts** to explore user creation, roles, permissions, and account lifecycle within Office 365.
- **Explore key features like calendar management** to gain insights into scheduling, event organization, and collaboration tools.
- **Configure calendar permissions and delegate access rights** to ensure precise control over calendar visibility and editing capabilities.
- **Set up shared calendars** to facilitate effective team communication and resource management.

<h2>Documentation</h2>

In this lab we will focus on how to use and manage Office 365 and explore the different features it has. We can try **Microsoft Office 365** for free for one month through their website. After entering our information, we should be able to access and use it for our own lab.

<p align="center">
<img src="https://i.imgur.com/uTWqSmg.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
<br />
<br />

With our information added, we can now begin exploring Office 365. Key features include the Users section, where we can manage user accounts, add new users, and reset passwords. In Teams, we can collaborate seamlessly through chats, group discussions, and scheduling meetings. Finally, the Subscriptions section allows us to manage payment methods, view invoices, and monitor license usage for active subscriptions.

<p align="center">
<img src="https://i.imgur.com/7NHPiaT.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
<br />
<br />

  
Lets take a look into “Users” on the left hand side and select “Active Users”.

<p align="center">
<img src="https://i.imgur.com/NuVRMoQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


Now, let's create a user by selecting Add a user. We will create a user named Bob Brown, with the display name Bob Brown and the username Bob123. The domain will be @SimoTech123.onmicrosoft.com. Click Next. We will not assign Bob a product license at this time, so we'll select Next again.

<p align="center">
<img src="https://i.imgur.com/icUXrLi.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
<br />
<br />

  
Next, we have the option to grant Bob administrative access, such as Helpdesk, Teams, Exchange, or User administration. For now, Bob will receive no admin controls. Click Next, then select Finish to complete the user creation process.

<p align="center">
<img src="https://i.imgur.com/0wzg5ac.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


We have successfully added Bob. A password will be auto-generated for him. Additionally, we can save these configurations as a template in case we need to create another user with the same settings in the future.

<p align="center">
<img src="https://i.imgur.com/HaMCFvd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


If we select the Print button, we can send Bob his credentials.

<p align="center">
<img src="https://i.imgur.com/q0m026d.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


Now we have a newly user added “Bob Brown”.

<p align="center">
<img src="https://i.imgur.com/1gobxwV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


Clicking on Bob Brown's profile reveals a wealth of details, including his username, group memberships, contact information, and last sign-in activity. Additionally, it provides options to Sign out of all sessions, reset his password, block sign-in access, or even delete the user account.

<p align="center">
<img src="https://i.imgur.com/7DpAzYd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


In the Licenses and apps tab, we can also assign licenses or products to Bob.

<p align="center">
<img src="https://i.imgur.com/7k3cjVC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


Now, let's delete the user Bob Brown and recover him. First, select Delete User, then click on Delete user to confirm.

<p align="center">
<img src="https://i.imgur.com/8Sz19NB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


Now, if we head over to the left side panel and select Deleted Users, we can find Bob Brown's account. Select his account, and then we can restore him.

<p align="center">
<img src="https://i.imgur.com/Pw4HlIe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


<p align="center">
<img src="https://i.imgur.com/GeuQOdV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


Now, let's create a user who will have a product and license. Navigate to Active Users, then select Add a user. Name the user Sam Sung, and set the username to Sam123.

<p align="center">
<img src="https://i.imgur.com/xaXrxeP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


Assign the user with the Microsoft 365 Business Standard license. 

<p align="center">
<img src="https://i.imgur.com/jVeEfFN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

  
Select “Next” then “Finish”.

<p align="center">
<img src="https://i.imgur.com/gdlThcm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


Now, let's assume that Sam will no longer be working with the company, and we need to remove his licenses and disable his account. To do this, click on Sam, then select the Licenses and apps tab. Uncheck Microsoft 365 Business Standard, and click Save changes.

<p align="center">
<img src="https://i.imgur.com/kL0NAGW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


Next, select Block sign-in, check the box for Block this user from signing in, and then click Save changes.


<p align="center">
<img src="https://i.imgur.com/ZvzYzOO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<p align="center">
<img src="https://i.imgur.com/XKZqe9N.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


Let's now create a user with licenses. Name the user Chill Guy and assign the necessary licenses and apps for the user.

<p align="center">
<img src="https://i.imgur.com/QR5mdeS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


Once we finish creating the user, select Chill Guy, then navigate to the Mail tab.

<p align="center">
<img src="https://i.imgur.com/15Tx4jB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


Select Read and Manage permissions, then add ourselves to the list. This will give us the ability to add and remove mailbox content, as well as read emails in Chill Guy's mailbox.

<p align="center">
<img src="https://i.imgur.com/J4TMDpu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


Let's also add ourselves to the Send on behalf of permissions, which allows us to send emails using both the mailbox name and Chill Guy's account name. The emails will indicate that they were sent on behalf of Chill Guy.

<p align="center">
<img src="https://i.imgur.com/4ogVmix.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


If we want to remove a device from a user, we need to navigate to Exchange by selecting Exchange on the left-hand side panel.

<p align="center">
<img src="https://i.imgur.com/gA6ukNE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


In Exchange, select the user, in this case, Chill Guy, then select Manage mobile devices on the bottom left.

<p align="center">
<img src="https://i.imgur.com/TL9X4Gn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


Even though there are no mobile devices listed, this is where an admin would manage them.

<p align="center">
<img src="https://i.imgur.com/y7XC92w.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


Let's enable Manage email forwarding by selecting Mailbox, then Manage email forwarding.

<p align="center">
<img src="https://i.imgur.com/egoyxK9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


Enable Forward all emails sent to this mailbox, and check the box for Deliver message to both forwarding address and mailbox.

<p align="center">
<img src="https://i.imgur.com/Un1VdSl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


Let's also manage automatic replies by selecting the Others tab and then selecting Manage automatic replies. Enable Automatic replies, and we can enter an automatic reply message in the message box.


<p align="center">
<img src="https://i.imgur.com/bpaSRc3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<p align="center">
<img src="https://i.imgur.com/t1uvm9b.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


Now, let's test this out by selecting the Apps icon in the top-left corner and then selecting Outlook.

<p align="center">
<img src="https://i.imgur.com/T1Zr5UH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


Then, we will open another mailbox by selecting the option in the top-right corner.

<p align="center">
<img src="https://i.imgur.com/ASXfkhX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


Next, search for Chill Guy and select OK. Now, we are in Chill Guy’s Outlook.

<p align="center">
<img src="https://i.imgur.com/XpBL3D4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


Now, let's test the automatic reply by going back to our primary mailbox and sending an email to Chill Guy.

<p align="center">
<img src="https://i.imgur.com/wopa4Uq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


Chill Guy’s Mailbox

<p align="center">
<img src="https://i.imgur.com/xzkbc4X.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

Our primary mail box

<p align="center">
<img src="https://i.imgur.com/xfosLKd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


We can conclude that the **automatic replies** are working.
Now, let's look into **calendar rights** in Office 365. Open the **Calendar**, then right-click on **My calendar** and select **Sharing and Permissions**.

<p align="center">
<img src="https://i.imgur.com/J6OFtV0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


Let's search for Chill Guy and add him as a Delegate for permissions. Check the box for Let delegate view private events, then select Share to finish.

<p align="center">
<img src="https://i.imgur.com/tJTIyNa.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


Back in Chill Guy’s mailbox, he will receive a notification that the sharing permissions have been enabled. He should click Yes to accept.

<p align="center">
<img src="https://i.imgur.com/z0uLFIZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


Now that we have delegation control as Chill Guy, we can set up important dates on our admin account that will appear on Chill Guy's calendar. Let's set up a test date on our admin account, such as Thanksgiving Day, and write an important message so that Chill Guy can see it.

<p align="center">
<img src="https://i.imgur.com/55Yuvd0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


<p align="center">
<img src="https://i.imgur.com/jQZp1yO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


On Chill Guy's calendar, we can see that the admin has added a message for Thanksgiving Day. With delegation, we have the option to edit it. Let's make some changes to the event.

<p align="center">
<img src="https://i.imgur.com/t0xP9ZY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


Double-click on the date, then select Edit on the top-left. Now, we can change anything we want. In this case, I will update the message to "No day off".

<p align="center">
<img src="https://i.imgur.com/O7HPS35.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


Back on our admin account we can see the changes to the message.

<p align="center">
<img src="https://i.imgur.com/MLVZHFK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

That concludes our lab on Office 365 congratulations!  We configured permission rights on Office 365 calendar and also delve into  setting up and configuring Office 365 services, managing user accounts, and exploring different key features.
