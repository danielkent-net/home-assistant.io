---
type: card
title: "Shopping List Card"
sidebar_label: Shopping List
description: "The Shopping List card allows you to add, edit, check-off, and clear items from your shopping list."
---

The Shopping List card allows you to add, edit, check-off, and clear items from your shopping list.

<p class='img'>
<img src='/images/dashboards/shopping_list_card.gif' alt='Screenshot of the shopping list card'>
Screenshot of the Shopping List card.
</p>

Setup of the [Shopping List integration](/integrations/shopping_list/) is required.

To add the Shopping List card to your user interface, click the menu (three dots at the top right of the screen) and then **Edit Dashboard**. Click the **Add Card** button in the bottom right corner and select from the card picker.

All options for this card can be configured via the user interface.

## YAML Configuration

The following YAML options are available when you use YAML mode or just prefer to use YAML in the Code Editor in the UI.

{% configuration %}
type:
  required: true
  description: "`shopping-list`"
  type: string
title:
  required: false
  description: Title of shopping list.
  type: string
theme:
  required: false
  description: Override the used theme for this card with any loaded theme. For more information about themes, see the [frontend documentation](/integrations/frontend/).
  type: string
{% endconfiguration %}

### Examples

Title Example:

```yaml
type: shopping-list
title: Shopping List
```
