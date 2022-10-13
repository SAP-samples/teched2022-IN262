# Configuring Integration Assessment Tool 

In this part if the exercise, you are taking the persona of a Integration Architect. As a Integration Architect, you are responsible for configuring the landscape for your organization.These steps will guide on doing your organization setup  

## Steps for Configuring the Tool 

Run through the following steps

From the Integration Assesement Tool:

1. Select “Configure” to open up Configure Sub-Menu
<br><img src="/exercises/ex2/images/1.0 Ex3_Select_Configure.png" width=80% height=80%>

2. Select “Vendors” – This is where one would configure all Vendors in your organization which will be used for an application or an integration technology. Select Create to Create Vendor
<br><img src="/exercises/ex2/images/2.0 Ex3_Select_Vendors.png" width=80% height=80%>

3. Name newly created Vendor as TechEd_SW_Provider_XX where XX is your assigned number. Change XX to your assigned number. Select “Create” to create the vendor
<br><img src="/exercises/ex2/images/2.1 Ex3_Create_and Name_Vendor.png" width=80% height=80%>

4. Select “Create” to create a new Vendor. 
<br><img src="/exercises/ex2/images/2.2 Ex3_Select_Create_Another_Vendor.PNG" width=80% height=80%>

5. Create another Vendor and cal it “Legacy_XX” where XX is your assigned number. Select “Create” to create the vendor. Create another Vendor called “Amazon”
<br><img src="/exercises/ex2/images/2.3 Ex3_Create_Another_Vendor.png" width=80% height=80%>



6. Select “Integration Technologies” – Representative middleware components. Integration technology profile - Indicates the software group. Integration technology instance - Actual runtime instance.


7. Select “Create” – This will enable us to create organization specific additional Technology Profile(s)

8. Enter/Select the following to create new Technology Profile
Name: TechEd_IN262_XX where XX represented the number assigned to you
Vendor: TechEd_SW_Provider_TR
Domains: Cloud2Cloud
Styles: Process Integration. **Note:** These values come from the Settings section
Select “Create”


9. Select “Technology Instance” – Here we will create Instance for applications from Technology Profile and also provide the Deployment Model such as On-Premise or Cloud etc. Select “Create”


10. Select the following:
Technology Profile: SAP Application Framework
Instance Name: AIF
Deployment Model: On-Premise
Select “Create” to create the Technology Instance


11. Create Additional Technology Instances using the details as per table:


12. Select “Applications” from the Configure Sub-Menu. 
Applications - Representative software solutions independent of deployment models 
Application profile - Indicates the software group
Application instance - Actual runtime component.


13. Select “Create”



14. Search for “Amazon” in the search bar and select the search icon  
Select “Amazon Web Services” from the List Box
Select Create
** Note: ** This is creating a Non-SAP Application with standard Application Profiles


15. Select “Create”



16. Select “Create Application Profile”
**Note:** Here we are creating custom Application Profile which is not standard and in most cases a home grown system


17. Enter the following:
Application Profile: Customer_Address_Book
Vendor: Legacy_TR
Select Create


18. Select newly created Application Profile “Amazon Web Services”. Select >


19. Select “Edit”


20. Select Vendor “Amazon” from te Drop-Down.
**Note** that this list of Vendors comes from Vendor configuration done previously. 


21. Select “Done”
Select “Application Profile” to go to the main landing page


22. Select “Application Instance”


23. Select “Create”


24. Select the following:
Application Profile: SAP ERP
Instance Name: ECC_OP_XX where XX represents your assigned group number
Deployment Model: On-Premise
Select “Create” to create the Technology Instance


25. Create Additional Application Instances using the details as per table:



26. 


    
## Summary

You should now have good understanding and familiarity of standard settings provided by SAP along with ability to Edit/Create existing or new settings.

Now, we Configure the tool specific to organizational landscape . Continue to - [1.3.1.	Configuring Integration Assessment Tool](/exercises/ex3)

