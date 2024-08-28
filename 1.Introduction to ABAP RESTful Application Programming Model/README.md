# Step 1 : Introduction to ABAP RESTful Application Programming Model

In this step, you will gain an understanding of the ABAP RESTful Application Programming Model (abbreviated as RAP) by exploring its  core layers i.e. Data Modeling & Behavior, Business Services Provisioning, and Service Consumption. You will review the overall architecture, examine the development flow, and explore different runtime implementation types for business objects. Finally, you'll dive into the specifics of Business Services and Business Objects, providing a solid foundation for working with the model.

<br>
The ABAP RESTful Application Programming Model consists of three main layers:

1. **Data Modeling & Behavior**
2. **Business Services Provisioning**
3. **Service Consumption**

## 1. Data Modeling & Behavior
The data modeling and behavior layer contains domain-specific business objects, which are defined with Core Data Services (CDS) and transactional behavior.

## 2. Business Services Provisioning
The business service provisioning layer consists of projection views with their projection behavior. These views focus on a particular aspect of the data model, which is exposed as business services through the OData protocol.

## 3. Service Consumption
The service consumption layer allows you to consume all types of OData services as well as OData Web APIs.

<br><br>
### First, we'll dive into the architecture overview.
<br>
<p align="center">
    <img src="../images/RAPArchitecture.png" alt="RAP Architecture"/>
    <p align="center"> Architecture Overview - The Big Picture</p>
</p>

<br><br>
### Now, let's examine the development flow in detail.
<br>
<p align="center">
    <img src="../images/RAPDetails.png" alt="RAP Development Flow"/>
    <p align="center"> Architecture Overview - Development Flow</p>
</p>

<br><br>
### Next, let's explore the Business object runtime implementation types.
<br>
<p align="center">
    <img src="../images/ManagedVsUnmanaged.png" alt="RAP Managed vs Unmanaged scenarios"/>
    <p align="center"> Architecture Overview - Development Flow</p>
</p>

<br><br>
### Finally, let's have a deeper look at Business Service and Business Object.

#### Business Service
<br>
<p align="center">
    <img src="../images/BusinessService.png" alt="Understanding Business Service"/>
    <p align="center"> Architecture Overview - Development Flow</p>
</p>

#### Business Object
<br>
<p align="center">
    <img src="../images/BusinessObject.png" alt="Understanding Business Object"/>
    <p align="center"> Architecture Overview - Development Flow</p>
</p>