# SOQL Queries

> SOQL does not have a direct "DISTINCT" keyword like SQL to retrieve distinct values from a query. However, you can achieve the functionality of a distinct query in SOQL using "GROUP BY" clause in conjunction with aggregate functions like "COUNT()," "SUM()," or "MAX()" to retrieve unique values. Here's an example:

```sql
SELECT FieldName__c, COUNT(Id) FROM ObjectName__c GROUP BY FieldName__c
```

```sql
SELECT Collaborator_Tier__c, COUNT(Contact_ID__c)
FROM Contact 
GROUP BY Collaborator_Tier__c

SELECT Collaborator_Approval_Status__c, COUNT(Contact_ID__c) 
FROM Contact 
GROUP BY Collaborator_Approval_Status__c
```

