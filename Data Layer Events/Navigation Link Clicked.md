# Navigation Link Clicked

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Navigation Link Clicked",
    "linkInfo": {
        "linkId": "<linkId>",
        "linkRegion": "<linkRegion>",
        "linkTarget": "<linkTarget>",
        "linkText": "<linkText>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|linkInfo.linkId|string|Identifier of the link clicked|act now, cancel, ok, 3456, 8765|||||||
|linkInfo.linkRegion|string|Click Event Detection data layer linkInfo.linkRegion||||||||
|linkInfo.linkTarget|string|Describes of the destination of a navigational link.|https:\/\/www.example.com|||||||
|linkInfo.linkText|string|Click Event Detection data layer linkInfo.linkText||||||||




