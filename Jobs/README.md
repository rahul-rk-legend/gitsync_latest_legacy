## Refresh Token Renewal Job
Token renewal job should be used to periodically update the refresh token configured for the integration. By default, the refresh token expires every 90 days, making integration unusable upon expiration. It is recommended to run this job every 7 or 14 days to make sure that refresh token will be up to date.


**Run Interval In Seconds:** 18000

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|Integration Environments|String|False|Default Environment|
|Connector Names|String|False|Microsoft Graph Mail Delegated Connector|

## Simple Job Example
This is an example of a simple job. It has 2 functions: if a case has a tag "Closed", it will close the case from the job, if a case has a tag "Currency", it will add a comment to the case.


**Run Interval In Seconds:** 18000

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|API Root|String|True|https://api.vatcomply.com|
|Verify SSL|Boolean|False|true|
|Password Field|Password|False|*****|

## Sync Table Record Comments
This job will synchronize comments in ServiceNow table records and Siemplify cases.


**Run Interval In Seconds:** 18000

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|Api Root|String|True|https://googlellcdemo3.service-now.com|
|Username|String|True|admin|
|Verify SSL|Boolean|False|false|
|Client ID|String|False||
|Use Oauth Authentication|Boolean|False|false|
|Table Name|String|True|incident|
|Password|Password|True|*****|
|Client Secret|Password|False|*****|
|Refresh Token|Password|False|*****|


adding a readme on