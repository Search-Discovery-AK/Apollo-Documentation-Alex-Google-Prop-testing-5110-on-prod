# Link Clicked

### This event is used for cases in which an anchor tag is used as a link.

For example, if an `<a>` tag is used to represent a  link, you would need to add these attributes to trigger the event to be collected when the anchor is clicked.

Do not include the “data-dom-event” data attribute on any other elements that you do not want to be tracked.

Check the implementation notes for data-dom-event descriptions.
```
<a
  data-dom-category="<category>"
  data-dom-category2="<category2>"
  data-dom-category3="<category3>"
  data-dom-category4="<category4>"
  data-dom-category5="<category5>"
  data-dom-component_ancestry="<component_ancestry>"
  data-dom-dom_event="<dom_event>"
  data-dom-identifier="<identifier>"
  class="class"
  data-dom-navigation_ancestry="<navigation_ancestry>"
>
```

## Parameters Definitions

|Data Attribute Name|Data Source Type|Data Source|Description|
| --- | --- | --- | --- |
|category|Custom Code|Custom Code|Optional fields that enable you to assign this link additional subcategories beyond category.|
|category2|Custom Code|Custom Code|Optional fields that enable you to assign this link additional subcategories beyond category.|
|category3|Custom Code|Custom Code|Optional fields that enable you to assign this link additional subcategories beyond category.|
|category4|Custom Code|Custom Code|Optional fields that enable you to assign this link additional subcategories beyond category.|
|category5|Custom Code|Custom Code|Optional fields that enable you to assign this link additional subcategories beyond category.|
|class|Static|Static|The list of HTML\/CSS classes applied to the link.|
|component_ancestry|Custom Code|Custom Code|A delimited string showing all components in the ancestry of the link clicked|
|dom_event|Custom Code|Custom Code|The value in the data-dom-event attribute|
|identifier|Custom Code|Custom Code|Optional fields that enable you to assign this link additional subcategories beyond category.|
|navigation_ancestry|Custom Code|Custom Code|The full URL of the link.|



