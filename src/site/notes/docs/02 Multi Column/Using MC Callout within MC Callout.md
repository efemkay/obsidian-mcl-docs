---
{"dg-publish":true,"dg-path":"02 Multi Column/Using MC Callout within MC Callout.md","permalink":"/02-multi-column/using-mc-callout-within-mc-callout/","noteIcon":"","updated":"2023-10-27T22:34:19.697+08:00"}
---


```
> [!multi-column]
> 
> > [!blank|no-margin pw2]
> > Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
> 
> > [!multi-column|pw6]
> > 
> > > [!tldr]- Manifest
> > > Contents
> > 
> > > [!info]- Backlog
> > > Contents
> > 
> > > [!tip] Project
> > > - ### Project A
> > > 	- completed
> > > - ### Project B
> > > 	- ongoing
```

- It will be easier if we think how to build this logically. Remember, in the above example, the main `[!multi-column]` contains two children i.e. `[!blank|no-margin pw2]` and `[!multi-column|pw6]`.
- The second (or nested `[!multi-column|pw6]`) then contains three (3) sub-callouts i.e. `[!tldr]- Manifest`, `[!info]- Backlog` and `[!tip] Project`

> [!info]
> 
> - `[!multi-column]` 
> 	1. `[!blank|no-margin pw2]`
> 	2. `[!multi-column|pw6]`
> 		1. `[!tldr]- Manifest`
> 		2. `[!info]- Backlog`
> 		3. `[!tip] Project`