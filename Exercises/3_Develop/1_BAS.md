
**Open SAP Business Application Studio**

1. Click Instances and Subscriptions under Services

2. Select the tab Subscriptions, and click on SAP Business Application Studio. You will be forwarded to your SAP Business Application Studio Home Page with automatic login to the application.
![](https://github.com/SAP-samples/teched2023-XP162/blob/main/Exercises/Images/clickBAS2.png)

3. Please, accept the Privacy Statement

![](https://github.com/SAP-samples/teched2023-XP162/blob/main/Exercises/Images/BAS_Privacy_Statment.png)

4. Browse the SAP Business Application Studio home page.
![](/images/Browse_BAS.png)


**Create a Dev Space in SAP Business Application Studio**

1. Click on Create Dev Space on the SAP Business Application Studio home page (or select "My Dev Spaces" if you already have one).
![](../images/Create_Dev_Space.png)


2. Enter a name of your choice for the space (for example, "devdemo") in the upper left corner and choose the application type SAP Fiori (Choosing SAP Fiori eases the creation of a deployable application compared to application type "Basics"). You don't have to select any additional SAP Extensions here. 

3. Click again **Create Dev Space** in the lower right corner. 

![](https://github.com/SAP-samples/teched2023-XP162/blob/main/Exercises/Images/Create_New_Dev_Space.png)
 
You will be forwarded to an overview of your dev space(s).

It may take some time until the newly created dev space is started. Once started the status changes from "STARTING" to "RUNNING” and the dev space name (in this case "devdemo") will turn into a blue hyperlink.

4. Click on the dev space link (e.g. "devdemo") to enter the space.

 ![](https://github.com/SAP-samples/teched2023-XP162/blob/main/Exercises/Images/Start_Devspace.png)

After a few seconds ...

 ![](https://github.com/SAP-samples/teched2023-XP162/blob/main/Exercises/Images/Start_BAS.png)

... you will see the Welcome Page of your dev space:

 ![](https://github.com/SAP-samples/teched2023-XP162/blob/main/Exercises/Images/landingBAS.png)

**Connect your SAP Business Application Studio with your Cloud Foundry Environment**

A connection of your SAP Business Application Studio to your Cloud Foundry subaccount is necessary if you want to deploy your application into your SAP BTP subaccount and make it available. 

**Preparation Steps** 

1. Switch to the SAP BTP cockpit and click on Overview of your subaccount (top left).
2. Check the **API Endpoint** and **Org Name** and your **Space**.
**Keep this information in mind** for the next steps (this is especially important if you want to use multiple subaccounts for your SAP Business Application Studio).

 ![](https://github.com/SAP-samples/teched2023-XP162/blob/main/Exercises/Images/API_Endpoint.png)
 



 

**Procedure for Connecting**

1. Switch to the tab where you have opened SAP Business Application Studio. In the tabs, click on View in the menu and select **Command Palette...** .

 ![](https://github.com/SAP-samples/teched2023-XP162/blob/main/Exercises/Images/Command_Palette.png)

2. Search or Select CF: Login to Cloud Foundry.

 ![](https://github.com/SAP-samples/teched2023-XP162/blob/main/Exercises/Images/Login_CF.png)
 
3. Ensure that the right cloud foundry API endpoint is entered (attention: when you copy&paste the API endpoint from the cockpit, make sure to remove spaces at the beginning or end of the URL).

4. Enter your SAP BTP account Email and Password when prompted. 

 ![](https://github.com/SAP-samples/teched2023-XP162/blob/main/Exercises/Images/Enter_email.png)

5. Select your Cloud Foundry Org (predefined).

6. Select the Space name (predefined).

 ![](https://github.com/SAP-samples/teched2023-XP162/blob/main/Exercises/Images/CF_Target.png)

 ![](https://github.com/SAP-samples/teched2023-XP162/blob/main/Exercises/Images/Logged_in.png)

**Now we have successfully created a connection between your SAP Business Application dev space and your SAP BTP Cloud Foundry space.**
 

## Summary

You've now successfully connected your SAP Business Application Studio, dev space and your SAP BTP Cloud Foundry space. Continue to - [2_Create app](https://github.com/SAP-samples/teched2023-XP162/blob/main/Exercises/3_Develop/2_Create%20app.md)
