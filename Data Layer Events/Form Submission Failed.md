# Form Submission Failed

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Form Submission Failed",
    "form": {
        "formError": "<formError>",
        "formField": [
            {
                "fieldID": "<fieldID>",
                "fieldPosition": <fieldPosition>,
                "formFieldError": "<formFieldError>",
                "formSection": "<formSection>"
            }
        ],
        "formID": "<formID>",
        "formName": "<formName>",
        "formType": "<formType>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|form.formError|string|Error text or code describing a form error.  This is the form-level error.|Credit card declined, Required entries missing, EC3456, EC8976|||||||
|form.formField[n].fieldID|string|Unique identifier of a form field within a form. |first\_name, last\_name, addr\_line1, addr\_line2|||||||
|form.formField[n].fieldPosition|integer|Integer position of a form field within a form.  The first for field is position 1.|1, 2, 3, 4, 5||||1|||
|form.formField[n].formFieldError|string|Error text or code describing a form field error.  |email address invalid, date required. EC987767, EC4567|||||||
|form.formField[n].formSection|string|Describes the section of a form to which a form field belongs. Useful for reporting on complex forms.|address1, address2, cc info, terms acceptance|||||||
|form.formID|string|Unique identifier of a form. |F-0113, 2543, CU001, PI-0988|||||||
|form.formName|string|Plain text form name. Generally used if formID is not obtainable. |Payment Info, Mailing Address, Payment Address, Contact Us|||||||
|form.formType|string|Form type used for grouping of similar forms in reports.  |Address, Contact, Comment, Review, Payment|||||||




