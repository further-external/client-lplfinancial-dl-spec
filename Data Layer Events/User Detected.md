# User Detected

### This event is part of the page load sequence, including virtual page loads in the case of single page apps, and must be pushed between the `Page Load Started` and `Page Load Completed` events.

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "User Detected",
    "user": {
        "anonymousUserID": "<anonymousUserID>",
        "custKey": "<custKey>",
        "entityTag": "<entityTag>",
        "loginStatus": "<loginStatus>",
        "userType": "<userType>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|user.anonymousUserID|string|When a user is not logged in,, this captures an anonymous user id.||||||||
|user.custKey|string|Unique identifier of a customer.  Any id's considered PII must be hashed. ||||||||
|user.entityTag|string|The entity tag of the user|RCIS|||||||
|user.loginStatus|string|Describes the login state of the user|logged in, logged out, guest|||||||
|user.userType|string|Describes the type of the user.  Often used to differentiate customers from employees or associates. |employee, guest, agent, customer|||||||




