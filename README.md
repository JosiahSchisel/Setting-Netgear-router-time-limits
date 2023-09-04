<h1>OpenDNS to block Bad Stuff on my home network. I give all credit to NetworkChuck on YouTube for his instructions.</h1>



<h2>Description</h2>
The project consists of a simple step-by-step tutorial on how to set up OpenDNS for my router system to control my home network. DNS stands for Domain Name System which assigns name to the IP address for each URL. OpenDNS gives the user power to prevent me or my family from visiting sites on the assigned block list. OpenDNS is free.
<br />


<h2>Languages and Utilities Used</h2>

- <b>OpenDNS URL/website</b> 
- <b></b>

<h2>Environments Used </h2>

- <b>Windows 11 PRO
- Chrome Browser</b> 

<h2>Walk-through:</h2>

<p align="center">
Search for opendns.com and click on the Consumer tab then Learn More: <br/>
  
<img src="https://imgur.com/zJKQTXa.png" height="80%" width="80%" alt=""/>
<br />
  
<br />
Click on OpenDNS Home which is free to sign up.  <br/>

<img src="https://imgur.com/6ReIqYf.png" height="80%" width="80%" alt=""/>
<br />
<br />
Go ahead and fill in your information for a free account. <br/>

<img src="https://imgur.com/RBkPH0z.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
The next few steps are a little bit more tricky as they require you to log into your router firmware via your computer. This step will allow the OpenDNS to communicate with your router to use the OpenDNS servers instead of your internet provider server. If you look at the picture below you will see 2 IP addresses for the nameservers which are 208.67.222.222 and 208.67.220.220. Below that under Choose your device we will use the Home Routers tab. Click the home routers tab. <br/>
<img src="https://imgur.com/mWm4LPK.png" height="80%" width="80%" alt=""/>
<br />
<br />
Find your router by scrolling or searching the guide list in the Individual Router Configuration list. The router model can be found by looking directly on your router. In my case, my router is a Netgear and uses a Genie Web Interface Device Configuration. It also provides a step by step instructions I will click on this guide. The second image is a picture of the back of my Netgear router which shows a HTTP address that will need to be entered into a separate window to access your router's firmware settings. <br/>
<img src="https://imgur.com/OA7t0Cp.png" height="80%" width="80%" alt=""/>    <img src="https://imgur.com/22fUc6a.png" height="80%" width="80%" alt=""/>
<br />
<br />
Here I have entered the router http code in the search bar and entered my Username and Password to enter the Netgear Genie which is the firmware that controls my router settings. <br/>
<img src="https://imgur.com/Pp6eFmT.png" height="80%" width="80%" alt="s"/>
<br />
<br />
Here is a picture of my NetGear genie firmware. Some of the picture is cut off to protect my sensitive information. <br/>
<img src="https://imgur.com/ZjkDA37.png" height="80%" width="80%" alt=""/>

Next click on the Internet Tab in the Netgear genie firmware browser. In my specific browser, its found by clicking the Advanced tab then Setup tab then Internet setup tab (2nd picture below) <br/>
<img src="https://imgur.com/ZjkDA37.png" height="80%" width="80%" alt=""/> <img src="https://imgur.com/R2Xs1GE.png" height="80%" width="80%" alt=""/>

Next, enter the following DNS server codes as seen in the picture provided by OpenDNS Netgear Genie Web Interface Device Configuration page. <br/>
<img src="https://imgur.com/tu8R7IM.png" height="80%" width="80%" alt=""/>


Next, we will clear the DNS Cache on Windows 11. Follow the picture instructions to clear the DNS Cache.  <br/>
<img src="https://imgur.com/QOarqsr.png" height="80%" width="80%" alt=""/>

Next log in to the opendns using your email and password.  <br/>
<img src="https://imgur.com/PX1zXfl.png" height="80%" width="80%" alt=""/>

Once you log in you should see a page like this which will auto-populate your IP address.  <br/>
<img src="https://imgur.com/cKVu9vB.png" height="80%" width="80%" alt=""/>

Click the network button on the right side and in the next pic click on add this network.  <br/>
<img src="https://imgur.com/ypOliz0.png" height="80%" width="80%" alt=""/>
<img src="https://imgur.com/pmPFk5T.png" height="80%" width="80%" alt=""/>

Fill in the friendly name bar and click the done tab. On the next page click on the IP address to the right of your Labeled friendly name that you chose.  <br/>
<img src="https://imgur.com/S629947.png" height="80%" width="80%" alt=""/>

On the next page, you will see a web content filtering page. Under each subheading, you can click on the view tab to see what websites will be blocked. You can also click on the Manage individual domains tabs and enter websites that you want blocked.  <br/>
<img src="https://imgur.com/fecJe6P.png" height="80%" width="80%" alt=""/>


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
