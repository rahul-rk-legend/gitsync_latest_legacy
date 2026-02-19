# GitSync

## Integrations
|Name|Description|
|----|-----------|
|Google Chronicle|Google SecOps enables you to examine the aggregated security information for your enterprise going back for months or longer. Use Google SecOps to search across all of the domains accessed from within your enterprise. To enable the Google API client to communicate with the Backstory API you will need Google Developer Service Account Credential, https://developers.google.com/identity/protocols/OAuth2#serviceaccount.|
|Sample Integration|This is an educational integration designed to showcase the most common design patterns, when working with actions, connectors and jobs.|
|ServiceNow|An incident ticketing integration exchanges ticket data between your ServiceNow instance and Google SecOps system.|
|VirusTotalV3|VirusTotal was founded in 2004 as a free service that analyzes files and URLs for viruses, worms, trojans and other kinds of malicious content. Our goal is to make the internet a safer place through collaboration between members of the antivirus industry, researchers and end users of all kinds. Fortune 500 companies, governments and leading security companies are all part of the VirusTotal community, which has grown to over 500,000 registered users.This integration was created using the 3rd iteration of VT API.|


## Connectors
|Name|Description|Has Mappings|
|----|-----------|------------|
|Sample Integration - Simple Connector Example|This is an example of a simple connector. It's integrated with "api.vatcomply.com" service and provides all of the main design ideas necessary to build a stable connector. Dynamic List defines what rates should be returned for a given currency and expects input in the format "EUR" etc.|True|
|ServiceNow Connector|Fetching incidents from ServiceNow to Siemplify|True|
|VirusTotal - Livehunt Notifications Connector|Pull information about Livehunt notifications and related files from VirusTotal. Note: this connector requires a premium API token. Dynamic list works with "rule_name" parameter.|True|


## Playbooks
|Name|Description|
|----|-----------|
|Playbook Default||
|Playbook Default 1||
|Playbook  Latest Legacy Folder 1||
|Playbook Latest Legacy Folder 1||


## Visual Families
|Name|Description|
|----|-----------|
|Family Testing Latest Legacy 1|Family Testing Latest Legacy 1|
|Family Testing Latest Legacy 2|Family Testing Latest Legacy 2|
|Family Testing Latest Legacy 3|Family Testing Latest Legacy 3|


## Jobs
|Name|Description|
|----|-----------|
|Simple Job Example|This is an example of a simple job. It has 2 functions: if a case has a tag "Closed", it will close the case from the job, if a case has a tag "Currency", it will add a comment to the case.|
|Sync Table Record Comments|This job will synchronize comments in ServiceNow table records and Siemplify cases.|

