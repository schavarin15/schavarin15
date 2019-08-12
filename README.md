# schavarin15
Testing
 

Contents 

1.	Deployment	1 

1.1.	Pre-deployment steps	1 

1.1.1.	CRM Solution Deployment	2 

1.1.2.	Data Migration Process	2 

1.2.	Post-Deployment Steps	3 

1.2.1.	Remove/Delete Records	3 

1.2.2.	Update Records	3 

1.2.3.	Modify System Users	4 

1.2.4.	Verify Records Imported Successfully	4 

￼ 

 

Deployment 

Pre-deployment steps 

 

NOTE: user must be logged in as an System Administrator to deploy the solution and a Global Admin to enable mailbox modifications. One can check their roles by clicking on Users: 

 

Verify assets: 

SmallBusinessStarterPack_1_0_0_0 

RefreshedConnectionsUI_1_1_managed 

SharePointFormView_1_1_0_0_managed 

SparkleXRM_7_2_7_managed 

KraftwareAutoNumber_1_2_0_0_managed  

 

Gather the required solutions and Starter Pack into a folder to make installation simpler, we will need them in a bit. In total we should have five solutions:    

 

CRM Solution Deployment 

Data Migration Process 

Exporting 

Importing 

Updated Components: 

CRUD the folllowing after installation to fit needs: 

Security Roles, Processes, Forms, Dashboards 

Log in to your  desired Dynamics CRM Environment you want the solution installed 

Head over to Settings > click ‘Solutions’. Most SiteMaps should have the Settings located here. If using the Unified Interface go to step iv.  

 

 

If you are using the Unified Interface, go to the right and click the gear icon and open ‘Advanced Settings’ > Solutions. 

 

 

 

NOTE: The first four solutions MUST be imported before importing the 	SmallBusinessStarterPack. 

 

Import RefreshedConnectionsUI_1_1_managed 

Select Import  

Choose the file named:  RefreshedConnectionsUI_1_1_managed 

Verify solution information on next screen then click import   

Import  SharePointFormView_1_1_0_0_managed 

Select Import  

Choose the file named:  SharePointFormView_1_1_0_0_managed 

Verify solution information on next screen then click import   

Import  SparkleXRM_7_2_7_managed  

Select Import   

Choose the file named:  SparkleXRM_7_2_7_managed 

Verify solution information on next screen then click import    

Import KraftwareAutoNumber_1_2_0_0_managed 

Select Import   

Choose the file named:  KraftwareAutoNumber_1_2_0_0_managed 

Verify solution information on next screen then click import    

Import SmallBusinessStarterPack_1_0_0_0 

Select Import 

Choose the file named: SmallBusinessStarterPack_1_0_0_0 

Verify solution information on next screen then click import 

 

Post-Deployment Steps 

Remove/Delete Records 

Update Records 

Update Inactive Processes 

 

Update: Opportunity - New Opportunity Entered Notification to Owner 

Navigate to Settings > Solutions > SmallBusinessStarterPack  

Open process  

 

Open email, click Set Properties  

Remove and replace From field with an active user account that you want to send the email  

 

Click Save and Close  

Click Activate on the Process 

 

Update: Opportunity - Populate New Fields for BD 

Navigate to Settings > Solutions > SmallBusinessStarterPack   

Open process   

Click Activate at the top 

 

Click Save and Close   

 

Update: Opportunity – Send email to owner when record is updated 

Navigate to Settings > Solutions > SmallBusinessStarterPack 

Open process 

Open email, click Set Properties 

Remove and replace From field with an active user account that you want to send the email. Similar to the first process we updated 

Click Save and Close 

Click Activate on the Process 

 

Update SiteMap (Optional) 

Navigate to Solutions  > SmallBusinessStarterPack 

Client Extensions > Site Map 

 

Modify as needed 

Click ‘Save and Close’ 

 

 

Modify System Users 

Assign Business Units 

Assign Security Role 

Verify Records Imported Successfully 

 

 
