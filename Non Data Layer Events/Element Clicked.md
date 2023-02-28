# Element Clicked

### This event is used for cases in which a non-anchor tag is used as a link.

For example, if a `<button>` tag is used in combination with Javascript to represent a download link, you would need to add these attributes to trigger the event to be collected when the element is clicked.

Do not include the “data-dom-event” data attribute on any other elements that you do not want to be tracked.

Check the implementation notes for data-dom-event descriptions.
```
<button
  data-dom-category2="<category2>"
  data-dom-category3="<category3>"
  data-dom-category4="<category4>"
  data-dom-category5="<category5>"
  data-dom-dom_event="<dom_event>"
  data-dom-file_extension="<file_extension>"
  data-dom-file_name="<file_name>"
  class="class"
  data-dom-navigation_ancestry="<navigation_ancestry>"
>
```

## Parameters Definitions

|Data Attribute Name|Data Source Type|Data Source|Description|
| --- | --- | --- | --- |
|category2|Custom Code|Custom Code|Optional fields that enable you to assign this link additional subcategories beyond category.|
|category3|Custom Code|Custom Code|Optional fields that enable you to assign this link additional subcategories beyond category.|
|category4|Custom Code|Custom Code|Optional fields that enable you to assign this link additional subcategories beyond category.|
|category5|Custom Code|Custom Code|Optional fields that enable you to assign this link additional subcategories beyond category.|
|class|Custom Code|Custom Code|The list of HTML\/CSS classes applied to the link.|
|dom_event|Custom Code|Custom Code|The value in the data-dom-event attribute|
|file_extension|Custom Code|Custom Code|The value in the data-dom-file\_extension data attribute|
|file_name|Custom Code|Custom Code|The value in the data-dom-file\_name data attribute|
|navigation_ancestry|Custom Code|Custom Code|The full URL of the link.|



