**Create an SAP Fiori Application with "Start from template"**

1. Click on **New Project from Template** in the Welcome tab to create the project.
Alternative: Open the menu in the top left corner and go to **View > Command Palette ...** and search for ">new project". Select the command **SAP Business Application Studio: New Project from Template**

![](../images/BAS_start.png)

2. In the New Project Wizard select **SAP Fiori Application**.

Click **Start**.

![](../images/Template_Fiori_app.png)

3. In the **Template Selection** choose the following:

For the field **Template Type** choose **SAP Fiori** from the drop-down.
Select 'Basic' tile.


Choose **Next**.

![](../images/Template_UI5.png)

4. In the **Data Source and Service Selection** choose **None** for Data source, because we just create a "Hello World" without data binding.

5. Choose **Next**.

![](https://github.com/SAP-samples/teched2023-XP162/blob/main/Exercises/Images/Data_Source.png)


6. Under **Entity Selection** name your SAPUI5 view. This name will appear in the launchpad service for the app. We keep **"View1"** for now

Choose **Next**

![](../images/View1.png")

7. In the next step, <strong>Project Attributes</strong> choose names and a description for your "Hello World" app (examples see figure):

- Module name **helloworldui5**
- Application title **Hello World App Title**
- Application namespace **sap.btp**
- Description: **A Fiori Hello World application**

**Project folder path** and **Minimum SAPUI5 version** should not be changed

- Add deployment configuration to MTA project **Yes**
- Add FLP configuration **Yes**
- Configure advanced options **No**

Choose **Next**.

![](https://github.com/SAP-samples/teched2023-XP162/blob/main/Exercises/Images/Template_Project_Attributes.png)

8. In the next step, **Deployment Configuration** choose **Cloud Foundry** as a target.

Choose **None** for Destination name.

Choose Add application to managed application router?: **Yes**.

This is the standard html5 repository from launchpad service and eases deployment.

Choose **Next**.

![](https://github.com/SAP-samples/teched2023-XP162/blob/main/Exercises/Images/Deployment_Config.png)

9. The launchpad service needs some Fiori Launchpad Configuration data about the app. Choose names for the entries Semantic Object, Action, and Title (examples see figure)
(Optional: For more information about these data and features, see Intent-Based Navigation in a Nutshell).

Semantic Object: **helloworld**
Action: **show**
Title: **showhelloworld** 

![](https://github.com/SAP-samples/teched2023-XP162/blob/main/Exercises/Images/Fiori_Launchpad_config.png)

10. Choose **Finish**

*Note*, that it may take some time until all dependencies are installed.

11. Click on **Add Project to Workspace**

![](https://github.com/SAP-samples/teched2023-XP162/blob/main/Exercises/Images/addprojecttoworkspace.png)

12. After your App is generated, you should see this page and in the Explorer a new folder "helloworldui5".

![](../images/BAS_Project_App_Info.png)

13. Open your Projects folder via menu: **File > Open Folder** ... and enter **"/home/user/projects"**.

![](../images/Open_Projects_folder.png)
 
14. Click **OK**.


## Summary

You have now successfully created the application, continue to - [3_Test](https://github.com/SAP-samples/teched2023-XP162/blob/main/Exercises/3_Develop/3_Test.md)

