# aml-service-suryabhadragiri-gmail.com-
aml-service-suryabhadragiri@gmail.com   

## Anti Money Laundering Reporting Service

###Problem Statement

As a Bank it is our duty to effectively meet anti-money laundering (AML) mandates for regulatory 
and internal reporting. As a Senior Developer in the Payments Integration Team you are assigned to develop a 
AML Reporting REST API Service that will be called and consumed by internal systems in the bank.

###Requirements
The requirement is to write a SpringBoot application that consumes payment messages in different formats (XML, JSON, CSV) as provided in the resources folder and create an AML Rest API service that provides the following REEST API Endpoints. 

1. Total Amount Processed From All Files - GET Rest Endpoint: **/report/total-amount-processed**

    Example response payload:
    ```
    {
       "Total_Amount_Processed":{
          "Date":"20-MARCH-2020",
          "Total":5000
       }
    }
    ```  


2. List Of All Currencies Available and their  Total Amounts - GET Rest Endpoint: **/report/list-of-currency-total-amount**

    Example response payload:
    ```
    {
      "ZAR":4000,
      "USD":3500,
      "TZS":1400
    }
   ```  

4. Total Amounts Processed Per Country - Rest Endpoint: **/report/total-amount-processed-per-country**

    Example response payload:
    ```
    {
      "TZA":5000,
      "ZAR":3000,
      "KEN":1500
    }
    ```
    

###Technology Stack

To complete this task you are free to use any technology stack or programming language as you see necessary, 
However our preferred technology stack is as follows:

**Java 8+**

**Spring / Springboot**
 
**H2 or HSQLDB in-memory DB**


##Testing

**BONUS POINTS:** You are encouraged to write lots of unit tests when performing this exercise.

##DevOps

**BONUS POINTS:** You are encouraged to make your application a Docker Containerised Application.
