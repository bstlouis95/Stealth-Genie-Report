# Stealth-Genie-Report
Final Project 

And
Report

StealthGenie.apk






Prepared by: Benjamin Saint Louis
U01386995










Table of Contents
Abstract  pg. 3
Scenario Introduction pg. 3
Threat Actor pg. 3
Target pg. 3
Campaign pg. 3
The Exploit pg. 4
Stages of the Attack pg. 4
Reconnaissance pg. 4
Weaponizing pg. 4
Delivery pg. 4
Exploit pg. 5
Soltra/Edge Representation pg. 6
Install pg. 7
Command and Control pg. 7
Actions on Objectives pg. 7
Incident Handling Process pg. 8
Identification Phase pg. 8
Eradication and Recovery Phase pg. 8
Lessons Learned pg. 8
Exploit References pg. 9
References pg. 9





Abstract
The purpose of this paper is to explain the very difficult but, very rewarding process of remotely installing a spyware application like Stealth Genie. StealthGenie and many other applications are advertised to employers, parents, and significant others to monitor their children, employees, and spouses cell phone activity. These applications can be downloaded on any Android or IOS system but, there is some stipulations for the successful exploitation of a potential victims device. There are only two ways to install a spyware on a mobile device remotely and manually but, once this is complete all activity on that mobile device can be monitored remotely.
This document will write out a scenario that is the most realistic using the kill chain.
 
Scenario Introduction
Threat Actor
Hammad Akbar is the creator of StealthGenie and he has been charged with “conspiracy, selling and advertising a surreptitious interception device” according to NBC news (https://www.nbcnews.com/tech/security/maker-stealthgenie-cellphone-spyware-app-indicted-u-s-charges-n214356). But, for the purposes of this assignment I will be following the trail of an curious house wife Katie who wants to make sure her husband late night work stays are really done in the office.
Target
The target will be Katie’s husband, Jordan Samsung Galaxy Note S5 running Android 7.0 TouchWiz UI. Katie will have to successfully take Jordan’s phone long enough for her to jail break his phone and install an APK file she found through an undisclosed source (because Stealth Genie is not available online anymore).
Campaign
As we follow Katie she plans to pretend to be sleeping while her husband comes home around 3 AM and she waits until he is fast asleep. She will then pull out her husbands phone from the charger and take it over to her desktop she will then proceed with the jailbreaking process and once that is completed she will then pull out the flash drive with the APK file and install it through the root directory. Finally, she will successfully restore her husbands phone to its normal settings and she will be able to monitor all of his activities from her desktop at her convenience.


Stages of the Attack
Reconnaissance
After a long day of errands, cleaning, cooking, and making sure everything appears as normal Katie puts her children to bed and patiently waits for her husband. As usual he appears at odd hours of the night she waits until the morning to question her husband’s whereabouts. Jordan throws around office jargon but, Katie stays calm and makes sure she asked her husband for his phone to make sure he does not have the latest update. She also writes down the make and model, so she can look up the correct jail brake tutorial on YouTube.
Weaponizing 
After Katie drops her children at school she meets up with Khan a former employee at InvoCode (the company that Akbar was the CEO which distributed the StealthGenie app) whom she met through a mutual friend who has ties with the black market. She buys a flash drive which she hopes has the correct file and she is on her back home to finish off her day of grueling housework. Katie finishes her tedious cleaning and she hops on the internet to find the quickest way to Jailbreak her husbands phone without noticing. She learns all the steps from enabling the developer option and downloading a rooting kernel file she studies these steps even going as far as jailbreaking her own phone to test it out.
Delivery
After a week and perfecting her jailbreaking skills she is ready to deploy her tactics. Katie knows her husbands schedule and she knows Thursday nights are his longest nights because he is off Friday. Once her husband is fast asleep she quietly grabs his phone and head to her desktop his phone is already off so she holds the home and volume up key to enter developer mode  
 

Next she plugs his phone into her desktop so she can add the APK and the root kernel.
 
Exploit
Knowing her husband is running Android 5.1.1instead of the updated 7.0 allows Katie to successfully install the APK once the jail break has been successfully flashed to the device.
Below is an image of the application SuperSU that check if the devise is successfully rooted which  
 

 
Install
Once the kernel is successfully flashed installing the APK is simply dragging and dropping the file into the phones folder. Then turning on the device and installing the APK once the permissions to install outside source files is checked. Below is a picture of a root file where you place APK files in a directory.
 
Command and Control
Katie will install the desktop application used to monitor her husbands phone and she will receive information such as all call logs, text messages, and visited websites. And now all she has to  do now is wait and snoop.
Actions on Objectives
Katie can now view all her call logs she can throw away her USB drive with the APK file but, all she has to do to remain hidden is not allow her husband to see her desktop application which is password protected.



Indication Phase
As the weeks roll on Jordan notices his phone is incredibly slow when he accesses his web browser and his calls are frequently dropped without notice. This inconvenience is making his job difficult because he has to keep relations with his clients to inform them on how there investments are moving in the market. He takes his phone to a phone lab and they find his phone has rooted without his knowledge. 
Eradication and Recovery Phase
The only way to remove the spyware was completely factory reset Jordan’s phone to prevent further loss of information. His customers data files were not backed up on a external drive so he lost a lot of valuable information due to the vulnerability his outdated OS. To prevent this kind of attack on his mobile Jordan is urged to update his phone every time a patch is available download a malware scanner to prevent installation of malicious applications.
Lessons Learned
Although most mobile spyware have to be downloaded manually anybody can be careless and have spyware downloaded remotely or through social engineering. If Jordan did not have such high usage of his phone he could of possible went months without noticing this spyware. Updating your devices is a must and have anti-malware and virus protection is the first step to leaving yourself and your information secure












Exploit References
1.	StealthGenie
2.	Mobile Spyware

References
http://www.topsecuritysoftware.net/android-apps/android-spy-software-download-stealthgenie-mobile-spy-software/
https://www.ic3.gov/media/2014/140930.aspx
https://www.sans.org/newsletters/newsbites/xvi/78
https://www.nbcnews.com/tech/security/maker-stealthgenie-cellphone-spyware-app-indicted-u-s-charges-n214356
https://acisni.com/installing-mobile-phone-spy-software-step-by-step/
http://www.stealthandroidspy.com/
http://www.stealthandroidspy.com/how-it-works/
https://digital-forensics.sans.org/blog/2010/10/21/digital-forensics-scada-blackberry
http://spyzrus.net/remote-install-cell-spy-software-exposed/
https://www.nist.gov/sites/default/files/documents/forensics/8-Murphy-NIST-Mobile-Malware-normal.pdf

