# CTA Link Clicked

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "CTA Link Clicked",
    "linkInfo": {
        "linkCtaType": "<linkCtaType>",
        "linkId": "<linkId>",
        "linkRegion": "<linkRegion>",
        "linkText": "<linkText>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|linkInfo.linkCtaType|string|Click Event Detection data layer linkInfo.linkCtaType||||||||
|linkInfo.linkId|string|Identifier of the link clicked|act now, cancel, ok, 3456, 8765|||||||
|linkInfo.linkRegion|string|Click Event Detection data layer linkInfo.linkRegion||||||||
|linkInfo.linkText|string|Click Event Detection data layer linkInfo.linkText||||||||




