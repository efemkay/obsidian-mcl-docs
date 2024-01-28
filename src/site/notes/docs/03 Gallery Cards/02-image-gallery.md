---
{"dg-publish":true,"dg-path":"03 Gallery Cards/02-image-gallery.md","permalink":"/03-gallery-cards/02-image-gallery/","title":"Image Gallery","noteIcon":"","updated":"2024-02-08"}
---


## Overview
Image Gallery layout will allow you to create masonry like image gallery layout by placing image embed (i.e. `![[path/to/image.jpg]]`) in successive row of line. You can do this either by using callout metadata or defining the properties `cssclasses: image-gallery`

![image-gallery-langkawi-1.png](/img/user/image-gallery-langkawi-1.png)

> [!warning] Markdown image embed (i.e. `![](path/to/image.jpg)`) not supported
>
> Due to how Obsidian renders markdown image embed, I currently cannot implement Image Gallery using such syntax. So for this part, always use wikilink embed (i.e. `![[path/to/image.jpg]]`)


### Using callout metadata

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


### Using properties declaration
Alternative to using callout metadata, you can create image gallery in your note by defining `image-gallery` in the note's `cssclasses` properties. Then insert embedded images (i.e. `![[path/to/image.jpg]]`). Put next to each other (with single spacing) for same row placement. Add single empty line to create new row. Example on raw markdown is shown below.

> [!info] Visit Obsidian's Help (link here [Properties - Obsidian Help](https://help.obsidian.md/Editing+and+formatting/Properties)) to know how to add properties to your note


```md
---
cssclasses:
  - image-gallery
---

![[path/to/pic1.jpg]] ![[path/to/pic2.jpg]]

![[path/to/pic3.png]] ![[path/to/pic4.png]] ![[path/to/pic5.png]]

```

Note that with frontmatter declaration, you have to put the image embed syntax on same line if you want it to stack side by side in LP. Reading View is more robust and is okay with single line break for same row and empty line for creating new row

> **Syntax below only works with Reading View**
> ```md
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

## Additional Controls

If you have Style Settings plugin installed, you may control the following aspects (go to `Style Settings > Modular CSS Layout - Multi Column > Multi Column Callout`)
- **Hide Strange New World Indicators in Image Gallery**
	- Hide the SNW backlinks count indicator. Useful if you normally link to the same images in other notes as well
- **Gap Between Images**
	- Adjust the gap between images in the gallery. Default is 5px
- **Max Height for Images**
	- Set the maximum height for images in gallery can be. Aspect ratio is respected.
- **Max Width for Images**
	- Set the maximum width for images in gallery can be. Aspect ratio is respected.

## Credits

- Pictures in Gallery example are from Unsplash
  - [@ryaneof](https://unsplash.com/photos/Jh_Xk8RQtG0)
  - [@manish_tulaskar](https://unsplash.com/photos/o0TRwfgXhdw)
  - [@izuddinhelmi](https://unsplash.com/photos/dIArrAUjQV0)
  - [@jaysithutun](https://unsplash.com/photos/0dF2fJjTHCw)
  - [@ramzigraphy](https://unsplash.com/photos/WeiERYmWIT4)
