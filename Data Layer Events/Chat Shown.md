# Chat Shown

### 

## Javascript Code
```js
window.dataLayer09876 = window.dataLayer09876 || [];
dataLayer09876.push({ event_data: null });  // Clear the previous event_data object.
dataLayer09876.push({
  "event": "chat_view",
  "detailed_event": "Chat Shown",
    "event_data": {
        "proactive": <proactive>,
        "reactive": <reactive>
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|event_data.proactive|boolean|Count of time the user earned a cart promotion \(e.g., smart shopping cart\).|TRUE, FALSE|||||||
|event_data.reactive|boolean|Count of time a cart promotion \(e.g., smart shopping cart\) is displayed to the user.|TRUE, FALSE|||||||




