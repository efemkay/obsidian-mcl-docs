---
{"dg-publish":true,"dg-path":"06 Advanced/No Wrap Option.md","permalink":"/06-advanced/no-wrap-option/","noteIcon":"","updated":"2023-11-11T18:00:19.360+08:00"}
---

### No Wrap Option for `[!multi-column]`
This option will allow you to create single row multi column callout. Horizontal scrollbar will appear when the sub-callouts exceed the width of the `[!multi-column]`. To create no wrap multi column, use the following syntax i.e. `[!multi-column|no-wrap]`.

Here's an example markdown
```
> [!multi-column|no-wrap]
>
>> [!note]+ Work
>> your notes or lists here. using markdown formatting
>
>> [!warning]+ Personal
>> your notes or lists here. using markdown formatting
>
>> [!summary]+ Charity
>> your notes or lists here. using markdown formatting
```


> [!important] Limitation on No-Wrap Multi Column
>
> Width Control (different width for sub-callout) for now is not valid for No-Wrap Multi Column. Columns will be mostly follow the minimum width -- it has separate minimum width than the Wrapped Multi Column
