# Setup a phone on SkySwitch
Phone Walkthrough | SkySwitch
<h2>Description</h2>
As an MSP we look for reliable, accessible, and flexible solutions for our clients. We use SkySwitch to accomplish this for our customer’s phone systems. 
<br />

<h2>Program walk-through:</h2>

<p align="center">
•	Today we will be setting up our Fanvil phone system.
<br/>
<img src="https://i.imgur.com/1xzLMAO.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/
<br/>
<br/>
<br/>
<br/>
•	Go to https://skyswitch.com to setup your account if you don’t already have one. <br/>
<img src="https://i.imgur.com/4vf4bLW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/
<br/>
<br/>
<br/>
•	If an account is already created go to app.dashmanager.com , log in with your information
<br/>
<img src="https://i.imgur.com/0Kgcqgq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/
<br/>
<br/>
<br/>
•	Your page should now look like this <br/>
<br/>
<img src="https://i.imgur.com/kvm9db0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/
<br/>
<br/>
<br/>
•	Before we setup our domain, we are going to need a phone number to assign to it. <br/>
•	Go to the Telco tab, click phone numbers  <br/>
<img src="https://i.imgur.com/xSuAExN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/
<br/>
<br/>
<br/>
•	Go to the Purchasing Phone Numbers tab on the left side of the webpage, click on Rate Center and choose your state and rate center (city) <br/>
<img src="https://i.imgur.com/o4ymzsC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/ 
<br/>
<br/>
<br/>
•	You will now have a list of phone numbers you can purchase. Choose one and select Purchase Selected Phone Numbers <br/>
<img src="https://i.imgur.com/PLFv6Jf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
<br/>
<br/>
•	Now we can create our domain for our client company.<br/>
•	Go to PBX tab, click PBX <br/>
<img src="https://i.imgur.com/oXduQdO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
<br/>
<br/>
•	Click On Domains, Add Domain. You should now be here 
 <br/>
<img src="https://i.imgur.com/K6pnctI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
<br/>
<br/>
•	Put in your information for each tab and click Next <br/>
<img src="https://i.imgur.com/Akn1P3S.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
<img src="https://i.imgur.com/Ls1S8OB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
<img src="https://i.imgur.com/lnblVcZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
<img src="https://i.imgur.com/5zLzOoY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
<br/>
<br/>
<br/>
•	You will now have your domain show under your domain list, click it. <br/>
•	Click on Users, it you should now be here 
<br/>
<img src="https://i.imgur.com/zNawfAn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
<br/>
<br/>
•	We are going to start adding our users now. The first user I like to make is Reception. You can name it however you like, I like to use Front Desk. Give them whatever extension you would like. You will have to put an email in and you can just use noemail@noemail.com, and set them as a whatever user you need. I will choose Simple.<br/>
<br/>
<img src="https://i.imgur.com/mdI3T8t.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
<br/>
<br/>
•	Continue this process until you have the amount of users that you need, it should look something like this <br/>
<br/>
<img src="https://i.imgur.com/qozwljN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
<br/>
<br/>
<br/>
•	The next thing we are going to create is a Time Frame. Depending on how the company is ran they will want the front desk to get calls first, but if that employee had to step away you can make it to where the calls get forwarded to other phones within the building so calls don’t get ignored. 
<br/>
•	Click on Time Frames, Add Timeframe, name it Ring All, Save 
<br/>
<img src="https://i.imgur.com/cEfwHSH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
<br/>
<br/>
•	Then go back to users, click your Front Desk user, go to Answering Rules, Add Rule
<br/>
<img src="https://i.imgur.com/3IK06H5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
<br/>
<br/>
•	Change Time Frame to the Ring All we created, Enable Simulltaneous Ring, check the Enabled, Inlcude user’s extension, and Ring all user’s phones box. 
<br/>
•Add the extensions of your other users. You can also include a ring delay. I will choose 5 seconds. This will make it to where the front desk will get called for that many seconds and it will then transfer over to the other extensions after that time. Save.
<br/>
<img src="https://i.imgur.com/a9p69lI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
<br/>
<br/>
•	You Answering Rules section should now look like this
<br/>
<img src="https://i.imgur.com/1lIgtpr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
<br/>
<br/>
•	Before leaving the answering rule section you can adjust how long the phone will ring for (I suggest atleast 30 seconds). 
<br/>
•	Now for the most important part, adding the phones to your users. First thing you need to do is identify what kind of phone you’re using (mine is a Yealink MP56),plug your phone into power and internet, find the MAC address on the back of the phone, find the IP address in the network settings of your phone. 
<br/>
•	If your phone has been previously setup you will need to factory reset it so you can login using default credentials. You can search how to do this with your specific phone, my phone is able to default by going to settings, Debug, Reset and the factory reset option pops up
<br/>
•	Go to your user, Phones, Add Phone. Put in the Device Type and MAC address., click add. 
<br/>
<img src="https://i.imgur.com/R2f5mGm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
<br/>
<br/>
•	Now we need to login to the phone web portal using it’s IP address. Put the IP address into your browser, it will say it’s not secure, go to advanced, continue to that IP address. 
<br/>
<img src="https://i.imgur.com/ehssqIe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
<br/>
<br/>
•	Default login should be admin, admin 
<br/>
<img src="https://i.imgur.com/rvUWdXT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
<br/>
<br/>
•	navigate to settings, auto provision, set URL to match the domain syntax, http://sipcfg.io/cfg/  . (This is an address for a zero touch provisioning server that allows phones to get ahold of their provisioning server’s address). Confirm and auto provision
<br/>
<img src="https://i.imgur.com/L9C1WhU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
<br/>
<br/>
•	You will now have your phone setup within Skyswitch for that user. It will looking something like this
<br/>
<img src="https://i.imgur.com/IuNxiM9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
<br/>
<br/>
<br/>
•	Rinse and repeat until all your users are setup!
