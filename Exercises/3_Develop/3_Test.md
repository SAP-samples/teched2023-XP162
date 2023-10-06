**Now you can test and preview the UI application in SAP Business Application Studio**

1. Right click on your project folder "helloworldui5" and choose **Preview Application**. 

     ![](../images/Preview_Application.png)


2. Choose npm script: **start-noflp fiori run --open "intex.html?sap-ui-xx-viewCache=false"**

     ![](../images/Start_noflp.png)

A new browser tab opens with your app:

![](../images/App_generated_new.png)

Now let us **change the title of the app** to "HelloWorld".

3. Go to **Explorer** in the left navigation pane.

4. Open folder "**webapp**" and subfolder **view** (in our example View1). Click on the page title inside the blue box. The element ID "page" will be selected.

5. Change "{i18n>title}" to "Hello TechEd".

![](../images/View1_code.png)

You will see the changes in the application preview accordingly: "Hello World" instead of "Hello World App Title".

<!-- ![](../images/Hello_TechEd.png) -->
