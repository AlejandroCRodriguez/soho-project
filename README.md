# soho-project
This is my first project that I am posting on to GITHUB. 
This is a project that I did for my graduating term. The overall goal of this project is to focus on securing my Windows computer and reducing the attacker landscape on my device.
While this is a Small Office Home Office network setup, the focus is on the home office. The primary aspect is to spend a lot while maximizing my security. 
The documents related to this project were weekly reports on the project to my teacher. Along with my finalized document and my PowerPoint presentation for the project. The PowerPoint is not the recorded version. 

# Tools utilized Operational
Tennable Nessus Essentials
Powershell
Microsoft Windows Defender
Oracle VirtualBox
Firefox  | This is for the hardened browser in VirtualBox
Suricata | Present in the virtual machine

# Tools originally to be utilized and had significant difficulties

Originally planned on Wazuh
Attempted Security Onion

    The majority of the problems of utilizing either of the two SIEMs above is that there was not enough space on my storage for my PC to accommodate full usage of these programs. On the low end, it is 100GB, but the recommended amount from research is 200GB. 
    Outside of the SIEM, the virtual box is about 25GB in virtual size. 

# Virtual Box Settings
16GB of RAM
25GB of Storage (200GB Needed for SIEM)
64MB of Video Memory
1 Monitor only
Network:
Adapter 1 is enabled
Attached to NAT

# Steps undertaken

Step 1: The utilization of a vulnerability scanner. I downloaded Tennable Nessus Essentials from this link here: https://www.tenable.com/products/nessus/nessus-essentials 
Step 2: I created an account with this program. 
Step 3: I started scanning my device. It only took my computer about six minutes to finish the scan. 
Step 4: Interpret results. 
My scan delivered 225 results. 223 of these were informational results. 2 Results were rated medium
Step 5: Modify Microsoft Windows Defender with the information I had.
Step 6: Enable logging. 
For step 6, I had initially thought logging was on because I enabled logging at first with PowerShell. Upon double checking, it was not logging. So I went into Windows Defender to enable.
Step 7: VirtualBox Setup
Step 8: Harden the Firefox browser. Created a work profile that will wipe history, cookies, and not remember any passwords when logging in. 
Step 9: Implement Suricata
# The last step to undertaken to be considered 100% complete in my book is to implement a SIEM. Now at this current moment in time, I have not been successful. 
Step 10: Attempt to implement a SIEM, either WAZUH or Security Onion. 


