---
previewUrl: "/docs/docs-content/api/0.2.1/badge-demo.html"
---
# ion-badge

Badges are inline block elements that usually appear near another element. Typically they contain a number or other characters. They can be used as a notification that there are additional items associated with an element and indicate how many items there are.

```html
<ion-badge>99</ion-badge>

<!-- Colors -->
<ion-badge color="primary">11</ion-badge>
<ion-badge color="secondary">22</ion-badge>
<ion-badge color="warning">33</ion-badge>
<ion-badge color="danger">44</ion-badge>
<ion-badge color="light">55</ion-badge>
<ion-badge color="dark">66</ion-badge>

<!-- Item with badge on left and right -->
<ion-item>
  <ion-badge slot="start">11</ion-badge>
  <ion-label>My Item</ion-label>
  <ion-badge slot="end">22</ion-badge>
</ion-item>
```


<h2>Properties</h2> 

<dl>
<dt>
<h3>color</h3> 
<strong>Attribute:</strong>  <code>color</code>
<strong>Type:</strong> <code>string</code>
</dt>
<dd>The color to use from your Sass `$colors` map.
Default options are: `"primary"`, `"secondary"`, `"tertiary"`, `"success"`, `"warning"`, `"danger"`, `"light"`, `"medium"`, and `"dark"`.
For more information, see [Theming your App](/docs/theming/theming-your-app).</dd>

<dt>
<h3>mode</h3> 
<strong>Attribute:</strong>  <code>mode</code>
</dt>
<dd>The mode determines which platform styles to use.
Possible values are: `"ios"` or `"md"`.
For more information, see [Platform Styles](/docs/theming/platform-specific-styles).</dd>

</dl>

