# Step 9: Create Metadata Extension

A metadata extension separates annotation from business logic.

## Use

Metadata extension is used to enrich your CDS data model projection with UI metadata for the latter generation of an SAP Fiori elements-based **Employee** list report app. 

A metadata extension separates annotation from business logic.


## Perform the following steps to implement a metadata extension:

1.  Add an annotation of  _@metadata.allExtensions:true_  to the CDS view.
2.  Create a Metadata extension and write annotations for the view and its fields.
3.  Use ";" to separate fields.

### Metadata extensions to be created:

-  **zfe_c_employee_xx**:<a href="./Metadata Extension for zfe_c_employee_xx" target="_blank">:link:</a>Employee Metadata Extension for FE Demo.
-  **zfe_c_empservices_xx**:<a href="./Metadata Extension zfe_c_empservices_xx" target="_blank">:link:</a>Employee Service Metadata Extension for FE Demo.