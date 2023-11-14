# UI Element Clicked

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "UI Element Clicked",
    "linkInfo": {
        "linkRegion": "<linkRegion>",
        "uiElement": "<uiElement>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|linkInfo.linkRegion|string|Click Event Detection data layer linkInfo.linkRegion||||||||
|linkInfo.uiElement|string|Data layer location linkInfo.uiElement, which is set via the value from HTML attribute data-ea-ui-link||||||||




