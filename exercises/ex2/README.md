# Configuring Integration Assessment Tool 

In this part of the exercise, you are taking the persona of an Integration Architect. As an Integration Architect, you are responsible for configuring the landscape for your organization. These steps will guide you on doing your organization setup.

## Steps for Configuring the Tool 

Run through the following steps

From the Integration Assesement Tool:

1. Select “Configure” to open up Configure Sub-Menu
<br><img src="/exercises/ex2/images/1.0 Ex3_Select_Configure.png" width=80% height=80%>

2. Select “Vendors” – This is where one would configure all Vendors in your organization which will be used for an application or an integration technology. Select Create to Create Vendor
<br><img src="/exercises/ex2/images/2.0 Ex3_Select_Vendors.png" width=80%>

3. Name the newly created Vendor as **TechEd_SW_Provider_XX** where **XX** is your assigned number. Change **XX** to your assigned number. Select “Create” to create the vendor
<br><img src="/exercises/ex2/images/2.1 Ex3_Create_and Name_Vendor.png" width=80% height=80%>

4. Select “Create” to create a new Vendor
<br><img src="/exercises/ex2/images/2.2 Ex3_Select_Create_Another_Vendor.PNG" width=80%>

5. Create another Vendor and call it **Legacy_XX** where **XX** is your assigned number. Select “Create” to create the vendor. Create another Vendor called **Amazon**
<br><img src="/exercises/ex2/images/2.3 Ex3_Create_Another_Vendor.png" width=80%>

6. Select “Integration Technologies”. Select “Create” – This will enable us to create organization specific additional Technology Profile(s)
<br><img src="/exercises/ex2/images/3.0 Ex3_Select_Integartion_Technology_and_Create_Organization.png" width=80% height=80%>

7. Enter/Select the following to create new Technology Profile
    1. Name: **TechEd_IN262_XX** where **XX** represented the number assigned to you
    2. Vendor: **TechEd_SW_Provider_XX**
       
    Select “Create”
<br><img src="/exercises/ex2/images/3.1 Ex3_Create_Technology_Profile_new.png" width=50%>

8. In the newly created Technology profile, click "Edit" on the top right corner. Then select "Domains and Styles" subtab to add Integration Domain and Integration Style to the profile.
<br><img src="/exercises/ex2/images/3.1 Ex3_Edit_Technology_Profile_new.png" width=80%>

9. Click the "Add" button in the Domains section.
<br><img src="/exercises/ex2/images/3.1 Ex3_Edit_Technology_Profile_Add_Domains_new.png" width=80%>

10.  Select Domains: Cloud2Cloud, Cloud2OnPremise. Click "Add" button.
 
**Note:** These values come from the Settings section
<br><img src="/exercises/ex2/images/3.1 Ex3_Add_New_Domain_new.png" width=50%>

11. Click the "Add" button in the Styles section.
<br><img src="/exercises/ex2/images/3.1 Ex3_Edit_Technology_Profile_Add_Styles_new.png" width=80%>

12.  Select Styles: Process Integration, Data Integration. Click "Add" button.

 **Note:** These values come from the Settings section

<br><img src="/exercises/ex2/images/3.1 Ex3_Add_New_Style_new.png" width=50%>

13.  Click "Done" at the top right to save the configuration.
<br><img src="/exercises/ex2/images/3.1 Ex3_Edit_Technology_Profile_Save_new.png" width=80%>

8. Select “Technology Instance” – Here we will create the Instance for Applications from the Technology Profile and also provide the Deployment Model such as On-Premise or Cloud, etc. Select “Create”
<br><img src="/exercises/ex2/images/3.3 Ex3_Select_Technology_Instance.png" width=80%>

9. Enter/Select the following:
    1. Technology Profile: SAP Application Interface Framework
    2. Instance Name: **AIF_XX** where **XX** represents the number assigned to you. 
    3. Deployment Model: On-Premise
    
    Select “Create” to create the Technology Instance
<br><img src="/exercises/ex2/images/3.4 Ex3_Select_Technology_Instance_Details.png" width=40%>

10. Create Additional Technology Instances using the details as per table. **Note** Replace XX with group number assigned to you.
<br><img src="/exercises/ex2/images/3.5 Ex3_Create_Additional_Technology_Instances.png" width=50%>

11. Select “Applications” from the Configure Sub-Menu
    1. Applications - Representative software solutions independent of deployment models 
    2. Application profile - Indicates the software group
    3. Application instance - Actual runtime component

    Select “Create”
<br><img src="/exercises/ex2/images/4.0 Ex3_Select_Applications.png" width=80%>

12. Search for any **Non-SAP** application. In the screen shot provided, we have selected “Amazon”   
    1. Select **Any Non-SAP Application**
    2. Select Create

    **Note:** This is creating a Non-SAP Application with standard Application Profiles. Also, any given instance would have only one instance of the application and hence you will not be seeing applications which are already created example **Amazon**
<br><img src="/exercises/ex2/images/4.3 Ex3_Create_Application_Profile_Details.png" width=40%>

13. Select “Create"
    
    **Note:** Here we are creating custom Application Profile which is not standard and in most cases a home grown system
<br><img src="/exercises/ex2/images/4.4 Ex3_Create_Application_Profile_Additonal.png" width=80%>

14. Select “Create Application Profile”. Enter the following:
    1. Application Profile: Customer_Address_Book_XX
    2. Vendor: Legacy_XX
    
    Select Create
<br><img src="/exercises/ex2/images/4.5 Ex3_Create_Application_Profile.png" width=40%>


15. Select newly created Application Profile “Amazon”. Select >
<br><img src="/exercises/ex2/images/4.7 Ex3_Select_Application_Profile.png" width=80%>

16. Select “Edit”
<br><img src="/exercises/ex2/images/4.8 Ex3_Select_Edit.png" width=80%>

17. Select Vendor “Amazon” from the Drop-Down and select Done
Select “Application Profile” to go to the main landing page
<br><img src="/exercises/ex2/images/4.9 Ex3_Select_Amazon_Drop_Down.png" width=80%>

18. Select “Application Instance” and "Create"
<br><img src="/exercises/ex2/images/5.0 Ex3_Select_Application_Instance.png" width=80%>

19. Select the following:
    1. Application Profile: SAP ERP
    2. Instance Name: ECC_OP_XX where XX represents your assigned group number
    3. Deployment Model: On-Premise
    
    Select “Create” to create the Technology Instance
<br><img src="/exercises/ex2/images/5.1 Ex3_Create_Application_Instance_Details.png" width=40%>

20. Create Additional Application Instances using the details as per table:
<br><img src="/exercises/ex2/images/5.2 Ex3_Create_Additional_Application_Instance_Details.png" width=50%>

## Summary

You should now have configured the Integration Assessment Tool as per your organization landscape.

Now, we create a Business Solution Request. Continue to - [Create Business Solution Request](/exercises/ex3)

