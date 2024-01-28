---
{"dg-publish":true,"dg-path":"06 Advanced/Callout Width Control.md","permalink":"/06-advanced/callout-width-control/","noteIcon":""}
---

When using a callout for [[docs/02 Multi Column/02-multi-column-callout\|MC Callout]], [[docs/02 Multi Column/03-float-callout\|Float Callout]] or [[docs/02 Multi Column/04-blank-callout\|Blank Callout]], you may use the width modifier below to have greater control on the callout width. There are three (3) approach to define the width i.e. fixed (pixel-based), responsive via percentage and responsive via dynamic width.

Apply the modifier in the callout metadata section i.e. `[!<callout-type>|<callout-metadata>]`. And as an example `[!info|pw3]`.

For MC Callout, please use it on the sub callouts e.g.
```
> [!multi-column]
>
>> [!note|dw-3]+ Work
>> your notes or lists here. using markdown formatting
>
>> [!warning|dw-2]+ Personal
>> your notes or lists here. using markdown formatting
>
>> [!summary|min-0]+ Charity
>> your notes or lists here. using markdown formatting
```

sdf

### Width Control
You can control sub-callout width by specifying the custom width option in the callout-metadata element (do NOT apply to `[!multi-column]` callout itself. So far, there's only a discrete options per below:
- `min-0` - to override and disable min width set in Style Settings
- `wide-2` - give callout twice the size
- `wide-3` - three times the size
- `wide-4` - four times the size
- `wide-5` - five times the size

### Fixed Width Modifier
| modifier | size implemented |
| -------- | ---------------- |
| `fw1`    | 100px            |
| `fw2`    | 200px            |
| `fw3`    | 300px            |
| `fw4`    | 400px            |
| `fw5`    | 500px            |
| `fw6`    | 600px            |
| `fw7`    | 700px            |
| `fw8`    | 800px            |
| `fw9`    | 900px            |

### Percentage Width Modifier
| modifier | size implemented |
| -------- | ---------------- |
| `pw1`    |10%|
| `pw2`    |18%|
| `pw3`    |28%|
| `pw4`    |38%|
|`pw5`|48%|
| `pw6`    |58%|
| `pw7`    |68%|
| `pw8`    |78%|
|`pw9`|88%|



### Dynamic Width Modifier
| modifier | size implemented |
| -------- | ---------------- |
| `mw0`    | no min size      |
| `dw1`    | 1x or min 200px  |
| `dw2`    | 2x of dw1 mw0    |
| `dw3`    | 3x of dw1 mw0    |
| `dw4`    | 4x of dw1 mw0    |
| `dw5`    | 5x of dw1 mw0    |
| `dw6`    | 6x of dw1 mw0    |
| `dw7`    | 7x of dw1 mw0    |
| `dw8`    | 8x of dw1 mw0    |
| `dw9`    | 9x of dw1 mw0    |


- fw1 = flex-basis: 100px
- fw2 = flex-basis: 200px
- fw3 = flex-basis: 300px
- fw4 = flex-basis: 400px
- fw5 = flex-basis: 500px
- fw6 = flex-basis: 600px
- fw7 = flex-basis: 700px
- fw8 = flex-basis: 800px
- fw9 = flex-basis: 900px



> [!info] When Pairing with sub-callout with min width
>
> By default, sub-callout within multi-column callout has min width of 200px (unless you changed it via Style Settings). Applying `wide-x` metadata for sub-callout that paired with those callout will have different sizing behaviour
