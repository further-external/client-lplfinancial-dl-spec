# Report Listing Item Clicked

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Report Listing Item Clicked",
    "listingItemClicked": {
        "listing": [
            {
                "report": {
                    "reportID": "<reportID>",
                    "reportType": "<reportType>"
                },
                "reportID": "<reportID>"
            }
        ]
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|listingItemClicked.listing[n].report.reportID|string|Unique ID for a Report||||||||
|listingItemClicked.listing[n].report.reportType|string|The type of the report|Transactions, Financial|||||||
|listingItemClicked.listing[n].reportID|string|Unique ID for a Report||||||||




