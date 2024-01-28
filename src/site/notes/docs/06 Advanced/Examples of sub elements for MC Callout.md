---
{"dg-publish":true,"dg-path":"06 Advanced/Examples of sub elements for MC Callout.md","permalink":"/06-advanced/examples-of-sub-elements-for-mc-callout/","noteIcon":""}
---

MC Callout supports a few markdown components as the children elements. Primary element is another callout (aka sub callouts). Alternatively, you can use dataview block, blockquote, paragraph or list block. See examples below on how to use it with MC Callout.

---

### Callouts as sub elements
```markdown
> [!multi-column]
> 
> > [!info] Title
> > Contents
> 
> > [!important] Title
> > Contents
> 
> > [!question] Title
> > Contents
```

---

### Dataview block as sub elements
```
> [!multi-column]
> 
> ``'dataview
> table without id file.link
> from "sample data A"
> ```
> 
> ``'dataview
> table without id file.link
> from "sample data B"
> ```
> 
> ``'dataview
> table without id file.link
> from "sample data C"
> ```
```

---

### Blockquote as sub elements
```
> [!multi-column]
> 
> > quotes
> 
> > quotes
> 
> > quotes
```

---

### Paragraphs as sub elements
```markdown
> [!multi-column]
> 
> paragraph 1. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Vitae nunc sed velit dignissim sodales. In cursus turpis massa tincidunt dui ut ornare lectus.
> 
> paragraph 2. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Vitae nunc sed velit dignissim sodales. In cursus turpis massa tincidunt dui ut ornare lectus.
> 
> paragraph 3. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Vitae nunc sed velit dignissim sodales. In cursus turpis massa tincidunt dui ut ornare lectus.
```

---

### List items as sub elements
`Markdown recognise two list block one after another (even with multiple empty lines) as just single list block. The workaround is to have <br> tag in the middle`

```markdown
> [!multi-column]
> 
> - list 1
> 	- sub list
> - list 1 (a)
> 
> <br/>
> 
> - list 2
> 	- sub list
> - list 1 (a)
> 
> <br/>
> 
> - list 3
> 	- sub list
> - list 1 (a)
```
