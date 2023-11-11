---
{"dg-publish":true,"dg-path":"02 Multi Column/01 Multi Column.md","permalink":"/02-multi-column/01-multi-column/","title":"Multi Column","noteIcon":"","updated":"2023-11-11T12:27:13.390+08:00"}
---


# Multi Column

> CSS snippet file: [MCL Multi Column.css](https://github.com/efemkay/obsidian-modular-css-layout/blob/main/MCL%20Multi%20Column.css)

This snippet will allow you to re-shape the either callout or (unordered) list and position them side by side. See each subsection for more details on how to control that. In summary this snippet has the following features

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

- Multi column layout using custom callout `[!multi-column]`
	- to be used with sub callout or codeblocks
- Invisible container using custom callout `[!blank-container]`
	- to be used as grouping container like a dashboard
- Multi column bullet list at (a) note level, and (b) block level
- Side/Floating column using callout-metadata `<left|right>`
	- use `[!<anycallout>|<left-or-right>-<size>]` to affect only Reading View or `[!<anycallout>|float-<left-or-right>-<size>]` to also apply in Live Preview.


> [!warning]
> For this features to work, please make sure your Obsidian **Installer** version is at v1.1.9 or higher as per screenshot below. Note that in Obsidian the "Current version: v1.x.x" is the App version while "(Installer version: v1.x.x)" is the **Installer** version I'm referring to above.
> 
> ![0b2fa16129e322205240958a971b27325ed39764png 658×160 obsidianmd](https://forum.obsidian.md/uploads/default/original/3X/0/b/0b2fa16129e322205240958a971b27325ed39764.png)

---

**< [[docs/02 Multi Column/01 Multi Column\|Multi Column Home]] | [[docs/02 Multi Column/01 Multi Column\|Multi Column Home]] | Next: [[docs/02 Multi Column/02-multi-column-callout\|MC Callout]] >** 