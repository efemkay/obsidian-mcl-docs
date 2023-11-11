---
{"dg-publish":true,"dg-path":"06 Advanced/Examples of sub elements for MC Callout.md","permalink":"/06-advanced/examples-of-sub-elements-for-mc-callout/","noteIcon":"","updated":"2023-11-11T18:44:17.266+08:00"}
---


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
>  | file.link                                                                                       |
> | ----------------------------------------------------------------------------------------------- |
> | [[sample data A/Correlation does not imply causation.md\|Correlation does not imply causation]] |
> | [[sample data A/Descriptive Statistics.md\|Descriptive Statistics]]                             |
> | [[sample data A/Exploratory data analysis.md\|Exploratory data analysis]]                       |
> 
{ .block-language-dataview}
> 
>  | file.link                                                               |
> | ----------------------------------------------------------------------- |
> | [[sample data B/Generalized linear model.md\|Generalized linear model]] |
> | [[sample data B/Logistic regression.md\|Logistic regression]]           |
> 
{ .block-language-dataview}
> 
>  | file.link                                                                     |
> | ----------------------------------------------------------------------------- |
> | [[sample data C/Errors and residuals.md\|Errors and residuals]]               |
> | [[sample data C/Goodness of fit.md\|Goodness of fit]]                         |
> | [[sample data C/Mean and predicted response.md\|Mean and predicted response]] |
> 
{ .block-language-dataview}
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
