# Page Load Started

### Page Load Started is part of the page load sequence, including virtual page loads in the case of single page apps, and must be the first event pushed in the page load event sequence.

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Page Load Started",
    "page": {
        "pageCategory": "<pageCategory>",
        "pageName": "<pageName>",
        "pageTitle": "<pageTitle>",
        "pageType": "<pageType>",
        "siteName": "<siteName>",
        "subsection": "<subsection>",
        "subsection2": "<subsection2>",
        "subsection3": "<subsection3>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|page.pageCategory|string|General category or Site Section of the page. Top level of page hierarchy.|Home, About Us, Shop, Account, Blog, Investors|||||||
|page.pageName|string|Describes the page and its content specifically. |product - XYZ123, Mens - Tops - Sweaters, Order Confirmation|||||||
|page.pageTitle|string|HTML title tag for the page||||||||
|page.pageType|string|Describes what purpose the page serves. Often aligns with the CMS template.|Home, Event Detail, Property Detail, Product Listing, Blog Post, Shopping Cart|||||||
|page.siteName|string|Common language used within the business to refer to the website. May be specific County Sites.|Prospecting-EU, Prospecting-US, Member Portal, Shop-CA, Shop-US, Shop-EU|||||||
|page.subsection|string|First sub-level of hierarchy under pageCategory or Site Section. |Shop &gt; Kids, Shop &gt; Mens, Shop &gt; Womens|||||||
|page.subsection2|string|Second sub-level of hierarchy under pageCategory or Site Section. |Shop &gt; Kids &gt; Tops, Shop &gt; Mens &gt; Shoes|||||||
|page.subsection3|string|Third sub-level of hierarchy under pageCategory or Site Section. |Shop &gt; Kids &gt; Tops &gt; Tees, Shop &gt; Mens &gt; Shoes &gt; Oxfords|||||||




