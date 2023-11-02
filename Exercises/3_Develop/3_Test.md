**Now you can test and preview the UI application in SAP Business Application Studio**

1. Right click on your project folder "helloworldui5" and choose **Preview Application**. 

     ![](https://github.com/SAP-samples/teched2023-XP162/blob/main/Exercises/Images/Preview_Application.png)


2. Choose npm script: **start-noflp fiori run --open "intex.html?sap-ui-xx-viewCache=false"**

     ![](https://github.com/SAP-samples/teched2023-XP162/blob/main/Exercises/Images/Start_noflp.png)

A new browser tab opens with your app:

![](https://github.com/SAP-samples/teched2023-XP162/blob/main/Exercises/Images/App_generated_new.png)

Now let us **change the title of the app** to "Hello TechEd".

3. Go to **Explorer** in the left navigation pane.

4. Open folder "**webapp**" and subfolder **view** (in our example View1). Click on the page title inside the blue box. The element ID "page" will be selected.

5. Change "{i18n>title}" to "Hello TechEd".

![](https://github.com/SAP-samples/teched2023-XP162/blob/main/Exercises/Images/View1_code.png)

You will see the changes in the application preview accordingly: "Hello TechEd" on the page.

<!-- ![](../images/Hello_TechEd.png) -->


## Summary

You have now successfully viewed your application, let's build and deploy, go to the next card or if in GitHub continue to - [4_Build](https://github.com/SAP-samples/teched2023-XP162/blob/main/Exercises/3_Develop/4_Build.md)
