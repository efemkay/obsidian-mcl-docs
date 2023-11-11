---
{"dg-publish":true,"dg-path":"02 Multi Column/01 Multi Column.md","permalink":"/02-multi-column/01-multi-column/","title":"Multi Column","noteIcon":"","updated":"2023-11-11T15:12:34.262+08:00"}
---


## Overview

This module (*direct link to snippet: [MCL Multi Column.css](https://github.com/efemkay/obsidian-modular-css-layout/blob/main/MCL%20Multi%20Column.css)*) provides you the option to reshape either callout or (unordered) list and position them side by side. This will give the appearance of multi columns. See each features section below for more details on how to control that.

- **[[docs/02 Multi Column/02-multi-column-callout\|MC Callout]]**  #mcl/list-card
	- allow for multiple columns setup using either sub callouts or any of the acceptable markdown components
- **[[docs/02 Multi Column/03-float-callout\|Float Callout]]** 
	- create a floating callout to either side of the screen (but still within readable line length) and allow text to flow around it
- **[[docs/02 Multi Column/04-blank-callout\|Blank Callout]]** 
	- use it to house other things like List Column or List Grid so that it can render in Live Preview
- **[[docs/02 Multi Column/05-list-column\|List Column]]**
	- Create a multi column list items that flows cotinuously
- **[[docs/02 Multi Column/06-list-grid\|List Grid]]** 
	- Create a multi column list items that creates new column for each main bullet
- **[[docs/02 Multi Column/07-list-card\|List Card]]** 
	- Create a card like layout from list items

---

## Cheat Sheet

Below is a cheat sheet once you already familiar with MCL. To understand how MCL works follow the links above or go through the guided navigation below.

### Multi Column (MC) Callout
| Callout Type      | Metadata modifier                  | Sub-elements                  |
| ----------------- | ---------------------------------- | ----------------------------- |
| `[!multi-column]` | `no-wrap` <br>`icons` <br>`flex-h` | see [[docs/06 Advanced/Callout Width Control\|Callout Width Control]] |

### Float Callout
| Callout Type | Metadata Modifier 1    | Metadata Modifier 2 | Metadata Modifier 3                |
| ------------ | ---------------------- | ------------------- | ---------------------------------- |
| any callout  | `<empty>`  <br>`float` | `left`  <br>`right` | `small`  <br>`medium`  <br>`large` |

### Blank Callout
| Callout Type      | Metadata modifier                  | Sub-elements                  |
| ----------------- | ---------------------------------- | ----------------------------- |
| `[!blank]` <br>`[!blank-container]` | `no-m` <br>`no-margin` | see [[docs/06 Advanced/Callout Width Control\|Callout Width Control]] |


### List Column / Grid / Card
| Type | Using Tag                                   | MD Attr plugin                                                                                                      | Frontmatter                                                                                 |
| ---- | ------------------------------------------- | ------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------- |
| LCol | `#mcl/list-column`                          | `two-column-list-block`  <br>`three-column-list-block`  <br>`four-column-list-block`  <br>`multi-column-list-block` | `two-column-list`  <br>`three-column-list`  <br>`four-column-list`  <br>`multi-column-list` |
| LGrd | `#mcl/list-grid`  <br>`#mcl/list-grid-wide` | -                                                                                                                   | `two-column-grid-list`  <br>`three-column-grid-list`                                        |
| LCrd | `#mcl/list-card`  <br>`#mcl/list-card-wide` | -                                                                                                                   | -                                                                                           |


---

**< [[docs/02 Multi Column/01 Multi Column\|Multi Column Home]] | [[docs/02 Multi Column/01 Multi Column\|Multi Column Home]] | Next: [[docs/02 Multi Column/02-multi-column-callout\|MC Callout]] >** 