# Step 7 : Create Service Definition

A **business service definition** (short form: service definition) describes **which CDS entities of a data model are to be exposed** so that a specific business service, for example, Sales Order handling, can be enabled. It is an ABAP Repository object that describes the consumer-specific but protocol-agnostic perspective on a data model. 
It can directly access the standard ABAP Workbench functionality, such as transports, syntax checks, element information, and activation. Its transport type is SRVD

## Use
A service definition represents the service model that is generically derived from the underlying CDS-based data model.

You use a service definition to define which data is to be exposed as a business service using one or more service bindings. A service definition itself is independent from the version or type of the protocol that is used for the business service

<br><br>
## As a part of this step, we shall be creating our Service Defintion to expose our Data Model Projections as service entities.
:warning:**Please note**: the number **xx** represents the assigned serial number to you.</span>

### Transactional views to Be Created:
- **zui_c_employee_services_xx**: <a href="./Service Definition zui_c_employee_services_xx" target="_blank">:link:</a> Service Definition for FE Demo.

<!-- TO DO Add Project specific photos here
<br><br>
### First, we'll dive into the architecture overview.
<br>
<p align="center">
    <img src="../images/RAPArchitecture.png" alt="RAP Architecture"/>
    <p align="center"> Architecture Overview - The Big Picture</p>
</p>
-->
