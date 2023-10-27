---
{"dg-publish":true,"dg-path":"02 Multi Column/03-float-callout.md","permalink":"/02-multi-column/03-float-callout/","title":"Float Callout","noteIcon":"","updated":"2023-10-27T22:34:48.356+08:00"}
---


## Overview
Float Callout will allow you to position side note or info box either to the left or right of the main note with other content wrapping around it. It uses callout-metadata to specify which side to float to and the size of the callout

### How To Use / Basic Syntax
1. Add `left` or `right` to the callout-metadata e.g. `[!info|right]`
2. Make sure the callout is above the paragraph that you want to have it wrapped around

Here is an example markdown
```markdown
### Main Article

> [!info|left]
> Addition note to the main article

Content of the main article
```

> Basic syntax will apply to Reading View. To make it work with Live Preview see Additional Controls below

> Previous version of Float Callout is a bit janky to edit in Live Preview. With the latest update, I managed to make it work quite nice. Do raise issue in GitHub if there's anything amiss.


## Additional Controls

### Adjust Width Definition
By default, the width of the callout will dynamically follow the content. You can make it fixed width by specifying the width option. There are 3 width option:
- `-small` - default width 300px
- `-medium` - default width 400px
- `-large` - default width 600px

Here's an example markdown
```markdown
## Main Article

> [!info|left-medium]
> Addition note to the main article

Content of the main article
```

### Apply to Live Preview
By default, if you only specify either left or right, Float Callout will only work in Reading View. If you want it to also work in Live Preview, prepend `float-` before the `left` or `right` e.g. `[!info|float-right]`

Here's an example markdown
```markdown
## Main Article

> [!info|float-left]
> Addition note to the main article

Content of the main article
```

### Combining the Additional Controls
You can also combine the above controls together. Here's an example markdown
```markdown
## Main Article

> [!info|float-left-medium]
> Addition note to the main article

Content of the main article
```

### Additional Global Settings via Style Settings
If you have Style Settings plugin installed, you may control the following aspects (go to `Style Settings > Modular CSS Layout - Multi Column > Float Callout`)
- Hide / Show SNW Indicator in Float Callout
- Adjust width definition for "small", "medium", and "large"
- Adjust margin top for Float Callout