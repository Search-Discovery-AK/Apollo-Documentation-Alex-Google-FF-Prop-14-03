# Download Link Clicked

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "file_download",
  "apollo_event": "Download Link Clicked",
    "event_data": {
        "component_ancestry": "<component_ancestry>",
        "file_extension": "<file_extension>",
        "file_name": "<file_name>",
        "identifier": "<identifier>",
        "region_ancestry": "<region_ancestry>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|event_data.component_ancestry|string|Captures the state or province associated with payments used for a transaction \(i.e. order, booking, dontation, etc.\).|Best Friends - Best Jeans, Puppy Love, Sail Away, Mens, Kids, Kids : Tops|||||||
|event_data.file_extension|string|Captures the city associated with a payment.|pdf, doc, csv, dmp, zip|||||||
|event_data.file_name|string|Captures the postal code associated with a transaction \(i.e. order, booking, dontation, etc.\).|Year End 2012.pdf, Operating Instructions.doc`|||||||
|event_data.identifier|string|Count of times that users completed the donation process.|act now, cancel, ok, 3456, 8765|||||||
|event_data.region_ancestry|string|Captures the currency used for currency-related actions.|Top Nav, Footer Nav, Hero, Recommended, Also Shopped, Also Bought|||||||




