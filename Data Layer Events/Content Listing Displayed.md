# Content Listing Displayed

### This event is part of the page load sequence, including virtual page loads in the case of single page apps, and must be pushed between the `Page Load Started` and `Page Load Completed` events.

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Content Listing Displayed",
    "listingDisplayed": {
        "listing": [
            {
                "content": {
                    "contentID": "<contentID>",
                    "contentTitle": "<contentTitle>"
                },
                "isDisplayed": <isDisplayed>
            }
        ],
        "listingType": "<listingType>",
        "resultsCount": <resultsCount>,
        "sortOrder": "<sortOrder>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|listingDisplayed.listingType|string|The type of results being listed|text, product, location, event, room, product location|||||||
|listingDisplayed.listing[n].content.contentID|string|Unique identifer of the content.||||||||
|listingDisplayed.listing[n].content.contentTitle|string|Title of a piece of content. |50 ways to use jello, Another look at pandas, Year end giving|||||||
|listingDisplayed.listing[n].isDisplayed|boolean|Helper node used by AA Product String Builder to set product scoped events|true|||||||
|listingDisplayed.resultsCount|integer|The total number of items returned that matched the search criteria. \(Integer\)|1, 21, 111, 166||||0|||
|listingDisplayed.sortOrder|string|Indicates the sort order.|high-low, low-high, nearest-farthest, a-z, newest-oldest|||||||




