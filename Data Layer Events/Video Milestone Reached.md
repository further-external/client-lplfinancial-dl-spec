# Video Milestone Reached

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Video Milestone Reached",
    "video": {
        "categoryName": "<categoryName>",
        "milestone": "<milestone>",
        "secondsLength": <secondsLength>,
        "videoID": "<videoID>",
        "videoName": "<videoName>",
        "videoPlayerType": "<videoPlayerType>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|video.categoryName|string|Category of the Video||||||||
|video.milestone|string|The milestone being tracked as an integer less than 100|25, 50, 77, 99|||||||
|video.secondsLength|integer|The total length of the video in seconds|36, 67, 178, 600||||0|||
|video.videoID|string|Video ID|YT456789, BC4567890, 876546789|||||||
|video.videoName|string|Video Name|Twitch\_FPS, Age of Empires, Halo|||||||
|video.videoPlayerType|string|Video Player Type|youTube, bright cove, JW Player, vimeo|||||||




