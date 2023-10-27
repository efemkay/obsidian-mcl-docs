---
{"dg-publish":true,"permalink":"/docs/multi-column/04-blank-callout/","title":"Blank and Float Callout","noteIcon":"","updated":"2023-10-26T14:13:48.061+08:00"}
---


## Overview
Blank Callout layout is just to provide an invisible container (or div). It is useful in many scenarios such as:
- Creating floating picture with extensive caption
- Creating side note without callout decoratives (like the background color and so on)
- Invisible container for embedded images for a dashboard design
- Invisble container to render things in Live Preview which normally need Reading View like List Columns/Grid/Card

### How To Use / Basic Syntax
Insert a custom callout `[!blank-container]` or `[!blank]`. Here's an example markdown
```markdown
## Header

Main paragraph content

> [!blank-container]
> - list 1 #mcl/list-column
> - list 2
> - list 3
> - list 4

Next paragraph content
```

## Additional Controls


### No Margin Option
By default, Blank Callout still inherit the default margin and padding defined by Obsidian. To make it seamless with the note (in term of alignment, especially when doing List Column/Grid/Card for Live Preview) you can specify the `no-margin` option in the callout-metadata i.e. `[!blank-container|no-margin]`

Here's an example markdown
```markdown
## Header

Main paragraph content

> [!blank-container|no-margin]
> - list 1 #mcl/list-column
> - list 2
> - list 3
> - list 4

Next paragraph content
```