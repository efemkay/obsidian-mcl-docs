---
{"dg-publish":true,"dg-path":"03 Gallery Cards/04-image-float.md","permalink":"/03-gallery-cards/04-image-float/","title":"Image Float (Left/Right)","noteIcon":"","updated":"2023-10-27T22:52:17.896+08:00"}
---



## Float Left/Right in Reading View Only
- Use this syntax to enable image float in Reading View only. In Live Preview it will be displayed on different lines
- Syntax: `![[<imagefile.jpg>|<position>|<size>]]`
- Example: `![ryaneof-Jh_Xk8RQtG0-unsplash.jpg|right|300](/img/user/assets/ryaneof-Jh_Xk8RQtG0-unsplash.jpg)`

## Float Left/Right in Live Preview and Reading View
- Use this syntax to enable image float in both Live Preview and Reading View. In case you didn't notice, the difference is just prepending `float-` before the position.
- Syntax: `![[<imagefile.jpg>|float-<position>|<size>]]`
- Example: `![ryaneof-Jh_Xk8RQtG0-unsplash.jpg|float-right|300](/img/user/assets/ryaneof-Jh_Xk8RQtG0-unsplash.jpg)`

> Note that editing float in Live Preview will be a bit off (or "janky"). Navigate using keyboard instead of mouse/trackpad. Even better use Source Mode.


## External Images
Technically, the image float positioning can work with external link images but it is currently not aesthetically optimised (in term of gaps and other adjustment).

I will update this in the future. But if you must use it now, the syntax is `![<position>|<size>](<imagefile.jpg>)` and `![float-<position>|<size>](<imagefile.jpg>)`
