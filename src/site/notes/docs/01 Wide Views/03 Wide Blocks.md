---
{"dg-publish":true,"dg-path":"01 Wide Views/03 Wide Blocks.md","permalink":"/01-wide-views/03-wide-blocks/","title":"Wide Blocks","noteIcon":""}
---

## Overview
Wide Blocks layout will allow you to create a layout where the specific block can be wider than the note's width. Currently, only 3 block types supported i.e. Dataview, Table and Callout. It may be useful if you have a big table that's too wide or using Multi Column Callout and wanted fit more than 3 columns of callouts.


## Understanding the snippet
- CSS snippet file: [MCL Wide Views.css](https://github.com/efemkay/obsidian-modular-css-layout/blob/main/MCL%20Wide%20Views.css)
- This snippet will provide the following features
	- Wide views using YAML `cssClass: wide-<page/blocks>` for applying to a specific individual note
	- Wide views using vault-wide toggle for applying to all notes in your vault
		- will require Style Settings plugin to enable the feature

---

## Using YAML (specifying `cssClass`)

- CSS snippet: `MCL Wide Views.css`
- Custom CSS class available
	- `wide-page`
	- `wide-dataview`
	- `wide-table`
	- `wide-backlinks`

This snippet allow you to use Obsidian CSS class helper to enable any of the wide views. To use it, add the helper class in the YAML (frontmatter) of your note (which must be at the top of the note) like below.

```markdown
---
cssClass: wide-page
---

<the rest of your note>
```



## Examples

![wide-callout-with-mcc.png](/img/user/Examples/wide-callout-with-mcc.png)

![wide-table-main-eg.png](/img/user/Examples/wide-table-main-eg.png)

---

**< [[docs/01 Wide Views/02 Wide Page\|Wide Page]] | [[docs/01 Wide Views/01 Wide Views\|Wide Views]] | Next: [[docs/02 Multi Column/01 Multi Column\|Multi Column]] >** 