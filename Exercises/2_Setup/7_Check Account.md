**Check your created Subaccount**

Go back to your SAP BTP Cockpit by clicking on the browser tab "Trial Home ..."

In your new subaccount check the following:


1. Click **Instances and Subscriptions** under **Services** (#1 on the following figure). You should see that the following services have been subscribed:
     - SAP Business Application Studio
     - SAP Build Work Zone, standard edition
2. Click on **SAP Business Application Studio** (#4 on the figure). This will open SAP Business Application Studio.
3. Click on **SAP Build Work Zone, standard edition** (#5 on the figure). This will open the launchpad site directory.<br>

Note: If you get the error message "Access Denied". Your user has not been assigned the role collection "Launchpad_Admin". See card "5_Launchpad Admin role". Goto "Role Collections", click on **"Launchpad_Admin**" and assign the email address of your user.
  
![](https://github.com/SAP-samples/teched2023-XP162/blob/main/Exercises/Images/checks.png)
  
**Additional Checks**
  
Cloud Foundry - "Org Members" (#2 on the figure):
It will list all users you have added as administrators with the "Org Manager" role. Users you have added as developers have no Organization Role.
  
Security - "Users" (#3 on the figure):
You should see all users assigned to the subaccount. A click on the arrow adds details, including their role collections.

Go to the next card or if in GitHub Continue to - [1_BAS](https://github.com/SAP-samples/teched2023-XP162/blob/main/Exercises/3_Develop/1_BAS.md)
