[![Build status](https://travis-ci.org/IBMResearch/ibm-tabs.svg?branch=master)](https://travis-ci.org/IBMResearch/ibm-tabs)
[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/IBMResearch/ibm-tabs)

## \<ibm-tabs\>

Tabs are used to separate content into different panes.

Example:
<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="ibm-tabs.html">
    <link rel="import" href="ibm-tab.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<ibm-tabs selected="0">
  <ibm-tab>Item one</ibm-tab>
  <ibm-tab>Item two</ibm-tab>
  <ibm-tab>Item three</ibm-tab>
</ibm-tabs>
```

### Notable breaking changes between 1.x and 2.x (hybrid):

IronSelectableBehavior and IronMultiSelectableBehavior, which are used by
ibm-tabs, introduce multiple breaking changes. Please see the README for those
behaviors for more detail.
