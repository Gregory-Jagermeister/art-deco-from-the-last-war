---
banner: "[[banner-eberron.webp]]"
tags: 
  - Item
  - Inventory
status: Incomplete
created: <% tp.date.now("YYYY/MM/DD HH:mm:ss") %>
modified: <% tp.date.now("YYYY/MM/DD HH:mm:ss") %>
---

> [!narrative]
> _Provide a narrative description of the item, its significance, and any emotional or historical context._

## Overview
**Rarity**: 
<% await tp.system.prompt("Rarity (Common, Uncommon, Rare, Very Rare, Legendary)") %>

**Cost**: <% await tp.system.prompt("Cost (in gold pieces)") %>

**Description**:  
<% await tp.system.prompt("Provide a brief description of the item, including its appearance and any notable features.") %>

**Properties**:  
<% await tp.system.prompt("List any special properties or abilities the item has.") %>

## **History**:  
<% await tp.system.prompt("Provide any historical background or lore associated with the item.") %>

## **Usage**:  
<% await tp.system.prompt("Explain how the item is used, including any specific mechanics or dice rolls required.") %>

## **Location Found**:  
<% await tp.system.prompt("Where can this item typically be found or purchased?") %>

**Notes**:  
<% await tp.system.prompt("Additional information or notes about the item.") %>