---
{"dg-publish":true,"dg-path":"01 Wide Views/01 Wide Views.md","permalink":"/01-wide-views/01-wide-views/","title":"Wide Views","noteIcon":"","updated":"2023-11-19T09:41:19.222+08:00"}
---


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
	- `wide-dataview` -- require Contextual Typography plugin
	- `wide-table` -- require Contextual Typography plugin
	- `wide-backlinks`

This snippet allow you to use Obsidian CSS class helper to enable any of the wide views. To use it, add the helper class in the YAML (frontmatter) of your note (which must be at the top of the note) like below.

```markdown
---
cssClass: wide-page
---

<the rest of your note>
```

For wide-dataview and wide-table, you will need to install [Contextual Typography](https://github.com/mgmeyers/obsidian-contextual-typography) plugin.

## Example

<img src="https://user-images.githubusercontent.com/42369515/163697717-911d36b3-f505-49c2-803b-775f1d7fae9a.png" height="350px">

---

- Using Style Settings toggle (affecting vault wide)

---

**< [[docs/02 Installation\|Installation]] | Next: [[docs/02 Multi Column/01 Multi Column\|Multi Column Home]] >** 