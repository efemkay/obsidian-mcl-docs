---
{"dg-publish":true,"dg-path":"06 Advanced/Using MC Callout within MC Callout.md","permalink":"/06-advanced/using-mc-callout-within-mc-callout/","noteIcon":""}
---

With the release of [0.9.7 (github.com)](https://github.com/efemkay/obsidian-modular-css-layout/releases/tag/0.9.7) MCL now supports having `[!multi-column]` callout inside another `[!multi-column]` callout. That would make the example below possible.

![example MC within MC.png](/img/user/docs/assets/example%20MC%20within%20MC.png)

```markdown
> [!multi-column]
>
> Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
> 
> > [!multi-column|pw7]
> > 
> > > [!tldr]+ Manifest
> > > Contents
> > 
> > > [!info]+ Backlog
> > > Contents
> > 
> > > [!tip] Project Progress
> > > - Milestone A - completed
> > > - Milestone B - ongoing
```

### Understanding how to use it
It will be easier if we think how to build this logically. Remember, in the above example, the main `[!multi-column]` contains two children i.e. `<paragraph>` and `[!multi-column|pw7]`. The second (or nested `[!multi-column|pw7]`) then contains three (3) sub-callouts i.e. `[!tldr]- Manifest`, `[!info]- Backlog` and `[!tip] Project`

This means first level container splits the two with 30%-70% columns, and the second `[!multi-column|pw7]` uses that 70% column to house its three sub-callouts. Evidently in the screenshot, only two can fit (default width 200px) for the first row with the 3rd sub-callout goes to its own row.

> [!info] Outline of the above logic
> 
> - `[!multi-column]` 
> 	1. `<paragraph>`
> 	2. `[!multi-column|pw7]`
> 		1. `[!tldr]- Manifest`
> 		2. `[!info]- Backlog`
> 		3. `[!tip] Project Progress`