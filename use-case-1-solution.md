# Solution:
## Recommend a plan that suits the size of the organization (Contoso is a mid-sized organization with 300 users).

### Introduction
To help mitigate fraudulent emails in an organization, Microsoft 365 offers specific features designed to enhance email security. These are generally available in plans like Microsoft 365 Business Premium and Microsoft 365 E5, both of which include advanced threat protection features.

Here are some key tools and features included in these plans:

- Microsoft Defender for Office 365: Provides email threat protection, including anti-phishing, anti-spam, and anti-malware measures. It also includes advanced tools to detect and mitigate threats like spoofing and impersonation.
  
- Exchange Online Protection (EOP): Automatically included in all Microsoft 365 subscriptions, EOP protects against spam, malware, and known viruses.
  
- Safe Links and Safe Attachments: These features proactively protect against malicious URLs and attachments by analyzing them before they're accessed.

- Advanced Threat Analytics: Detects suspicious user or entity behavior to identify threats before they can cause harm.

- Reporting and Tracking: Enables administrators to monitor and investigate email traffic for potential fraudulent activity or unusual patterns.

The Microsoft 365 E5 plan is a great choice for organizations seeking more robust enterprise-grade security, as it offers the most comprehensive security features.

![Alt text](https://github.com/Chioma-Isiekwene/platform-contoso-fraudulent-email/blob/main/choosing%20the%20right%20plan.JPG)

### Connect the workplace 
Go to http://security.microsoft.com/
Choose a workplace (enter the  name of the workplace. E.g Contoso)
![Alt text](https://github.com/Chioma-Isiekwene/platform-contoso-fraudulent-email/blob/7b2265e5d20c53d8858af3719018f66bdc778abf/choose%20a%20work%20place.JPG)
Either of this two plan will suffice for the size of the organization. 
![Alt text](https://github.com/Chioma-Isiekwene/platform-contoso-fraudulent-email/blob/main/Review%20and%20finish%20workplace%20connection.JPG)
Review and finish workplace connection.

### This solution takes you through the configuration of that foundation in these steps:
1.	Determine your tenants
2.	Optimize your networking
3.	Synchronize your identities and enforce secure sign-ins
4.	Migrate your Windows devices, Office clients, and on-premises Office servers and data
5.	Deploy device and app management

## See the video below for more information: 
https://youtu.be/umhUNzMqZto

## Navigate to the Microsoft Defender portal
https://security.microsoft.com
 ![Alt text](https://github.com/Chioma-Isiekwene/platform-contoso-fraudulent-email/blob/main/learn%20more.JPG)

# Step 1: In the Microsoft 365 Defender page,  Go to the threat and vulnerability dashboard
	If there is an incident, it will show on the dashboard. 
 ![Alt text](https://github.com/Chioma-Isiekwene/platform-contoso-fraudulent-email/blob/main/go%20to%20dashbord.JPG)
 
# step 2: Check security posture
![Alt text](https://github.com/Chioma-Isiekwene/platform-contoso-fraudulent-email/blob/main/click%20improve%20score.JPG)
   - Safe Links and Attachments:
     	- Enable Safe Links to rewrite and scan URLs in emails.
    	 - Configure Safe Attachments to scan and block malicious files.
   - Email Authentication:
    	 - Set up SPF, DKIM, and DMARC protocols to prevent spoofing.
   - Preset Security Policies:
     	- Apply "Strict" preset security policies for maximum protection.

# step 3: check for highly privileged identities
![Alt text](https://github.com/Chioma-Isiekwene/platform-contoso-fraudulent-email/blob/main/highly%20priviledge%20identities.JPG)

# Step 4: Improve security posture by clicking “improve score” to reduce risk exposure
![Alt text](https://github.com/Chioma-Isiekwene/platform-contoso-fraudulent-email/blob/main/find%20hightest%20configuration%20priorities%20to%20address.JPG)

# Step 5: Find the highest configuration priority to address
![Alt text](https://github.com/Chioma-Isiekwene/platform-contoso-fraudulent-email/blob/main/threat%20alerts%20and%20recommendations.JPG)

# Step 6: Threat analysis ( view threat alerts and recommendations).
	Analyst report, Related incidents, Impacted assets, Recommendation report.
 ![Alt text](https://github.com/Chioma-Isiekwene/platform-contoso-fraudulent-email/blob/main/Threat%20analysis.JPG)
 
# Step 7: Monitor what is happening in real-time and take action against likely threats
![Alt text](https://github.com/Chioma-Isiekwene/platform-contoso-fraudulent-email/blob/main/business%20email%20compromise.JPG)

# Step 8: click on threat overview: Business Email Compromise
	(No permission granted, contact the global administrator)
On the dashboard of the incident report, you can see the type of incident, the severity, and the response. A more efficient way to see the incident is by viewing the incident graph. 
On the left of the tab, you can see the incident and how it played out, whose system is involved and the IP address.
Click on the device affected and isolate the device.
![Alt text](https://github.com/Chioma-Isiekwene/platform-contoso-fraudulent-email/blob/main/No%20permission%20granted.JPG)

# Step 9: Leverage the “tools” tab for documentation, sizing, readiness scripts, etc. Stakeholder Reports
   	- Mail Flow Reports:
	- Use the Exchange Admin Center ([admin.exchange.microsoft.com](https://admin.exchange.microsoft.com)) to generate mail flow reports, such as inbound/outbound messages and non-delivery details.
   	- Stakeholder Communication:
     	- Share periodic reports with stakeholders to ensure transparency and build trust.
![Alt text](https://github.com/Chioma-Isiekwene/platform-contoso-fraudulent-email/blob/main/Tools%20for%20documentation.JPG)

# Step 10: cloud storage and report generation.
![Alt text](https://github.com/Chioma-Isiekwene/platform-contoso-fraudulent-email/blob/main/Cloud%20for%20reporting%20and%20storage.JPG)

## Note: I leverage copilot in preparation for the above step to the solution. 


