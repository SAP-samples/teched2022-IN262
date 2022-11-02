# Create Interface Request  

In this part of the exercise, you are taking the persona of an Integration Developer. As an Integration Developer, you determine the right integration technology by processing an interface request. The Integration Developer also gets a proposal of the integration technology with the best fit to the specified requirements and decides on the integration technology.

## Steps for creating Interface Request

Run through the following steps from the Integration Assesement Tool Landing Page:

1. Click **Requests** to go back to the main landing page
<br><img src="/exercises/ex4/images/1.1_Ex4_Create_Request_Main_Page.PNG" width=80% height=80%>

2. Click **Interface Request**
<br><img src="/exercises/ex4/images/1.2_Ex4_Select_Interface_Request.PNG" width=80% height=80%>

3. Find Interface Requested created by you in previous exercise. This would be **Order2Cash_XX** where **XX** stands for your group number. Click **Requirement Analysis**
<br><img src="/exercises/ex4/images/1.3_Ex4_Select_Requirement_Analysis.PNG" width=80% height=80%>

4. Step 1 is Integration Use Case Patterns. Click **A2A Integration**. Click **Next Step**
<br><img src="/exercises/ex4/images/1.4_Ex4_Integration_Use_Case_Pattern.PNG" width=80% height=80%>

5. Step 2 is Transformation.
    1. Click **Yes**
    2. Click: **Simple Transformation**
    3. Click: **No** (B2)
    4. Click **Next Step**
<br><img src="/exercises/ex4/images/1.5_Ex4_Transformation.PNG" width=80% height=80%>

6. Step 3 is Integration Content. Click **Create**
<br><img src="/exercises/ex4/images/1.6_Ex4_Integration_Content_Create.PNG" width=80% height=80%>

7. Select on your scenario name which in the case of instructor is named **Order2Cash-1**
<br><img src="/exercises/ex4/images/1.61_Ex4_Integration_Content_Select_Request.PNG" width=40% height=40%>

8. The system will connect to API Business Hub to get the content
<br><img src="/exercises/ex4/images/1.62_Ex4_Integration_Content_Loading_API_Hub.PNG" width=40% height=40%>

9. The content from API Business Hub is displayed. Enter **Customer** in the search field. Select **Target Application**
<br><img src="/exercises/ex4/images/1.63_Ex4_Integration_Content_Enter_API_Request.PNG" width=80% height=80%>

10. Select:
    1. iFlow **Account Overview** Fetch customer related ServiceOrders, ContractAccount, Invoice, Locks, payments, MeterReadings, Acc balance and due date. -- Scroll down
    2. iFlow **Account Search**. 
    3. Select **Import**
<br><img src="/exercises/ex4/images/1.64_Ex4_Integration_Content_Select_iFlows_And_Import.PNG" width=80% height=80%>

11. Selected iFlow(s) are displayed. Select **Next Step**
<br><img src="/exercises/ex4/images/1.65_Ex4_Integration_Content_Next_Stept.PNG" width=80% height=80%>

12. Step 4 is Connectivity. Select
    1. Click **Yes**     - This question is about protocol conversion from source system to target system. For our interface request, this would be Yes
    2. Click **No**      - This question is for managing Trading Partner Management TPM. Since our Integrface Request does not have the need for TPM
    3. Click **Application Connectors**     - Checkbox selected
    4. Click **Technology Connectors**      - Checkbox selected
    5. Select **Next Step**
<br><img src="/exercises/ex4/images/1.7_Ex4_Connectivity.PNG" width=80% height=80%>

13. Step 5 is Monitoring_and_Operations. Select: 
    1. Click **Yes**    - This question is to provide monitoring ability to Business Users or no. 
    2. Click **Yes**    - This question is to provide monitoring ability forward technical errors or no.
    3. Select **Done**
<br><img src="/exercises/ex4/images/1.8_Ex4_Monitoring_and_Operations.PNG" width=80% height=80%>

14. This gives you the ability to see the responses entered and Edit if needed. Click **Go to Technology Selection**
<br><img src="/exercises/ex4/images/1.9_Ex4_Review_and_Goto_Technology_Selection.PNG" width=80% height=80%>

15. Click **Select Technology**. Here you can see the requests of your requirement analysis
<br><img src="/exercises/ex4/images/1.10_Ex4_Select_Technology.PNG" width=80% height=80%>

17. Selected Technologies are higlighted. Select relevant instance from the dropdown:
    1. For SAP Application Interface Framework select **AIF**
    2. For SAP Integration Suite, Cloud Integration, select **CI**
    
    **Note** These are the instance configured in previous steps.
    
    Select **Select**
<br><img src="/exercises/ex4/images/1.11_Ex4_Fill_Selected_Technology.PNG" width=80% height=80%>

18. Select **Submit**
<br><img src="/exercises/ex4/images/1.12_Ex4_Submit_Technology_Selection.PNG" width=80% height=80%>

18. Check if your Technology Name shows Completed. Click **Requests** to go back to the main landing page
<br><img src="/exercises/ex4/images/1.13_Ex4_Completed_Interface_Request_and_Return_to_Landing.PNG" width=80% height=80%>
    
## Summary

You should now have created an Interface Request.

Now, we analyse the usage of SAP Integration Suite. Continue to - [Analyse](/exercises/ex5)
