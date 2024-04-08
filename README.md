# Full-Field-Roster-API-
Full Field Roster API Changes R8/R9
Follow the steps below on creating the APIs
a)R8 Versions are into Regional Orgs and Production
b)R10 Versions into FCQA and Core Orgs
c) //(Note:Please insert the below values into SchemaKey only when your're newly deploying it into snowflake)       
 insert into public."SchemaKey" values ('PRIMARY', 'STATIC','ROC_FULL_FIELD_ROSTER_API__c', 'UNIQUE_ID', 'ROC_FULL_FIELD_ROSTER_PK', null, null, null, null);
