# Report Interaction Occurred

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Report Interaction Occurred",
    "reportAction": {
        "interactionDetail": "<interactionDetail>",
        "interactionType": "<interactionType>",
        "reports": [
            {
                "reportID": "<reportID>",
                "reportType": "<reportType>"
            }
        ]
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|reportAction.interactionDetail|string|Captures the interaction detail for an interaction that was performed with a report.|bar chart, table, calendar year|||||||
|reportAction.interactionType|string|Captures the type of interaction that was performed with a report.|chart type, date range|||||||
|reportAction.reports[n].reportID|string|Unique ID for a Report||||||||
|reportAction.reports[n].reportType|string|The type of the report|Transactions, Financial|||||||




