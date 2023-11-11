---
{"dg-publish":true,"dg-path":"03 Gallery Cards/02-image-gallery.md","permalink":"/03-gallery-cards/02-image-gallery/","title":"Image Gallery","noteIcon":"","updated":"2023-11-11T15:40:07.831+08:00"}
---


## Overview

Image Gallery layout will allow you to create masonry like image gallery layout by placing image embed (i.e. `![[path/to/image.jpg]]`) in successive row of line. There are 2 different ways you can do so i.e.

1. Using Obsidian Callout (by specifying the callout metadata `gallery`)
2. Using frontmatter (by specifying `cssclass: image-gallery`)


> [!warning] Markdown image embed (i.e. `![](path/to/image.jpg)`) not supported
>
> Due to how Obsidian renders markdown image embed, I currently cannot implement Image Gallery using such syntax. So for this part, always use wikilink embed (i.e. `![[path/to/image.jpg]]`)


### How to Use -- with Callout

- Insert callout (it will work with any callout) and enter `gallery` in the callout metadata. E.g.  `> [!info|gallery]`
- Insert transcluded/embedded images. Add empty lines in between the images to create new row. Images "grouped" between empty lines will be stacked side by side

```markdown
> [!blank-container|no-margin gallery] Title
>
> ![[path/to/pic1.jpg]]
> ![[path/to/pic2.jpg]]
>
> ![[path/to/pic3.png]]
> ![[path/to/pic4.png]]
> ![[path/to/pic5.png]]

```

#### Example

![](https://raw.githubusercontent.com/efemkay/obsidian-modular-css-layout/main/docs/assets/gallery-callout-langkawi.png)


### How to Use -- with Frontmatter `cssClass: image-gallery`

- Specify `cssClass: image-gallery` at the frontmatter *(top of your markdown notes fenced by two three-dashes `---`, see example below)*
- Insert embedded images (i.e. `![[path/to/image.jpg]]`). Put next to each other (with single spacing) for same row placement. Add single empty line to create new row.


```markdown
---
cssClass: image-gallery
---

![[path/to/pic1.jpg]] ![[path/to/pic2.jpg]]

![[path/to/pic3.png]] ![[path/to/pic4.png]] ![[path/to/pic5.png]]

```

> Note that with frontmatter declaration, you have to put the image embed syntax on same line if you want it to stack side by side in LP. Reading View is more robust and is okay with single line break for same row and empty line for creating new row
>
> **Syntax below only works with Reading View**
> ```markdown
> ---
> cssClass: image-gallery
> ---
>
> ![[path/to/pic1.jpg]]
> ![[path/to/pic2.jpg]]
>
> ![[path/to/pic3.png]]
> ![[path/to/pic4.png]]
> ![[path/to/pic5.png]]
>
> ```



#### Example

![](https://raw.githubusercontent.com/efemkay/obsidian-modular-css-layout/main/docs/assets/gallery-cssclass-langkawi.png)


## Credits

- Pictures in Gallery example are from Unsplash
  - [@ryaneof](https://unsplash.com/photos/Jh_Xk8RQtG0)
  - [@manish_tulaskar](https://unsplash.com/photos/o0TRwfgXhdw)
  - [@izuddinhelmi](https://unsplash.com/photos/dIArrAUjQV0)
  - [@jaysithutun](https://unsplash.com/photos/0dF2fJjTHCw)
  - [@ramzigraphy](https://unsplash.com/photos/WeiERYmWIT4)
