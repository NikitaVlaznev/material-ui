---
filename: /packages/material-ui/src/ExpansionPanelSummary/ExpansionPanelSummary.js
title: ExpansionPanelSummary API
---

<!--- This documentation is automatically generated, do not try to edit it. -->

# ExpansionPanelSummary

<p class="description">The API documentation of the ExpansionPanelSummary React component.</p>



## Props

| Name | Type | Default | Description |
|:-----|:-----|:--------|:------------|
| <span class="prop-name">children</span> | <span class="prop-type">node |   | The content of the expansion panel summary. |
| <span class="prop-name">classes</span> | <span class="prop-type">object |   | Override or extend the styles applied to the component. See [CSS API](#css-api) below for more details. |
| <span class="prop-name">expandIcon</span> | <span class="prop-type">node |   | The icon to display as the expand indicator. |

Any other properties supplied will be spread to the root element ([ButtonBase](/api/button-base)).

## CSS API

You can override all the class names injected by Material-UI thanks to the `classes` property.
This property accepts the following keys:
- `root`
- `expanded`
- `focused`
- `disabled`
- `content`
- `expandIcon`

Have a look at [overriding with classes](/customization/overrides#overriding-with-classes) section
and the [implementation of the component](https://github.com/mui-org/material-ui/tree/master/packages/material-ui/src/ExpansionPanelSummary/ExpansionPanelSummary.js)
for more detail.

If using the `overrides` key of the theme as documented
[here](/customization/themes#customizing-all-instances-of-a-component-type),
you need to use the following style sheet name: `MuiExpansionPanelSummary`.

## Inheritance

The properties of the [ButtonBase](/api/button-base) component are also available.
You can take advantage of this behavior to [target nested components](/guides/api#spread).

## Demos

- [Expansion Panels](/demos/expansion-panels)

