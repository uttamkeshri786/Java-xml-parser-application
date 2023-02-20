# Java

## 1. XML-XpathParser

**Steps:**
- Import XML-related packages.
- Create a DocumentBuilder.
- Create a Document from a file or stream.
- Create an Xpath object and an XPath path expression.
- Compile the XPath expression using XPath.compile() and get a list of nodes by evaluating the compiled expression via XPath.evaluate().
- Iterate over the list of nodes.
- Examine attributes.
- Examine sub-elements.

# Maven-Springboot 

## 2. SQL-Scripts (Pre-Requirement Analysis)

**Steps:**
- Understanding the base requirement for the creating the query scripts.
- create a Customer table (to be mapped internally through the main working set)
- Creates the sequence CUSTOMER_DETAILS_SEQUENCE in the sample schema. This sequence could be used to provide customer ID numbers when rows are added to the customers table.
- Using Indexes to provide faster access to data for operations that return a small portion of a table's rows
- creating object types with the the CREATE TYPE of name {CUST_NOTIFY} statement and the CREATE TYPE BODY statements to create the specification of an object type
- created queue CUSTOMER_DETAILS_Q for preprocessing the registration process & this queue is stored in our Queue Table CUSTOMER_DETAILS_QT.
- adding stored procedure CUSTOMER_DETAILS_ENQUEUE for enqueuing & set message properties, provided the payload.
- create a trigger CUSTOMER_DETAILS_INSERT_TRG allowing us to insert on customer table. 
