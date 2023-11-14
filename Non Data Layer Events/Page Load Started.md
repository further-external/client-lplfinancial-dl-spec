# Page Load Started

### 

## Variable Definitions

| Attribute Name|Data Source Type|Data Source|Description|
| --- | --- | --- | --- |
|Campaign Tracking (s.campaign)|Query String|cid|Description not provided|
|Host Name (s.server)|Custom Code|hostname;|Description not provided|
|Page view custom event|Static|1|Description not provided|
|Pardot ID|Custom Code|get("visitor_id405762")|The pardot ID from the datalayer.|
|URL (Full)|Custom Code|delete('sluser');
return url;|URL with email query string's removed|
|URL Path|Custom Code|pathname;|Description not provided|
|URL Query String|Custom Code|split('?');
return queryStrings[1];|Query Strings without emails|



