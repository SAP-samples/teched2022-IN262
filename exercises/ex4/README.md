# Create Interface Request  

In this part if the exercise, you are taking the persona of a Integration Developer. As a Integration Developer, you determine the right integration technology by processing an interface request. Integration Developer also gets a proposal of the integration technology with the best fit to the specified requirements and decides on the integration technology.

## Steps for creating Interface Request

Run through the following steps from the Integration Assesement Tool Landing Page:

1. Click **Requests** to go back to main landing page
<br><img src="/exercises/ex4/images/1.0_Ex3_Create_Request.PNG" width=80% height=80%>

2. Click **Interface Request**


3. Find Interface Requested created by you in previous exercise. This would be **Order2Cash_XX** where XX stands for your group number. Click **Requirement Analysis**


4. Step 1 is Integration Use Case Patterns. Click **A2A Integration**. Click **Next Step**


5. Step 2 is Transformation.
    - Click **Yes**
    - Click: **Simple Transformation**
    - Click: **No** (B2)
    - Click **Next Step**

6. Step 3 is Integration Content. Click: **Create**



7. Select on your scenario name which in the case of instructor is names **Order2Cash-1**


8. The system will connect to API Business Hub to get the content


9. Content from API Business Hub is displayed.
    - Enter **Customer** in the search field. Select **Target Application**


10. Select:
    - iFlow **Account Overview**. Scroll down
    - iFlow **Account Search**. 
    - Select **Import**


11. Selected iFlow(s) are displayed. Select **Next Step**


12. Step 4 is Connectivity. Select
    - Click **Yes**     - This question is about protocol conversion from source system to target system. For our interface request, this would be Yes
    - Click **No**      - This question is for managing Trading Partner Management TPM. Since our Integrface Request does not have the need for TPM
    - Click **Application Connectors**
    - Click **Technology Connectors**
    - Select **Next Step**


13. Step 5 is Monitoring_and_Operations. Select: 
    - Click **Yes**    - This question is to provide monitoring ability to Business Users or no. 
    - Click **Yes**    - This question is to provide monitoring ability forward technical errors or no.
    - Select **Next Step**

14. This gives you’re the ability see the responses entered and Edit if needed. Click **Go to Technology Selection**



15. Click **Select Technology**. Here you can see the requests of your requirement analysis


16. Selected Technologies are higlighted. Select relevant instance from the dropdown:
        - For SAP Application Interface Framework select **AIF**
        - SAP Integration Suite, Cloud Integration, select **CI**
    **Note** These are the instance configured in previous steps.
        - Select **Select**


17. Select **Submit**


18. Check if your Technology Name shows Completed. Click **Requests** to go back to the main landing page

    
## Summary

You should now have created Interface Request.

Now, we Analyse usage of Integration Suite. Continue to - [Analyse](/exercises/ex5)
