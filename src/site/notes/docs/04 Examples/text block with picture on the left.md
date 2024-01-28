---
{"dg-publish":true,"dg-path":"04 Examples/text block with picture on the left.md","permalink":"/04-examples/text-block-with-picture-on-the-left/","noteIcon":""}
---


![example text with side pic.png](/img/user/docs/assets/example%20text%20with%20side%20pic.png)

---

### Using [[docs/02 Multi Column/02-multi-column-callout\|MC Callout]] 
```md
> [!multi-column]
> 
>> [!blank|fw3]
>> ![dataran lang](https://upload.wikimedia.org/wikipedia/commons/thumb/6/6c/Eagle_square_at_Kuah_Langkawi.jpg/375px-Eagle_square_at_Kuah_Langkawi.jpg)
> 
> Langkawi, officially known by its sobriquet Langkawi, the Jewel of Kedah (Malay: Langkawi Permata Kedah), is a duty-free island and an archipelago of 99 islands (plus five small islands visible only at low tide in the Strait of Malacca) located some 30 km off the coast of northwestern Malaysia and a few kilometres south of Ko Tarutao, adjacent to the Thai border. Politically, it is an administrative district of Kedah, with Kuah as its largest town. Pantai Cenang is the island's most popular beach and tourist area.
```

---

### Using [[docs/02 Multi Column/03-float-callout\|Float Callout]] 
```md
> [!blank-container|float-left-fw3]
> ![300](https://upload.wikimedia.org/wikipedia/commons/thumb/6/6c/Eagle_square_at_Kuah_Langkawi.jpg/375px-Eagle_square_at_Kuah_Langkawi.jpg)
 
 Langkawi, officially known by its sobriquet Langkawi, the Jewel of Kedah (Malay: Langkawi Permata Kedah), is a duty-free island and an archipelago of 99 islands (plus five small islands visible only at low tide in the Strait of Malacca) located some 30 km off the coast of northwestern Malaysia and a few kilometres south of Ko Tarutao, adjacent to the Thai border. Politically, it is an administrative district of Kedah, with Kuah as its largest town. Pantai Cenang is the island's most popular beach and tourist area.
```

> Note: Empty line between Float Callout and paragraph needed to break the callout, else the paragraph will be part of the callout

---

### Using [[docs/03 Gallery Cards/04-image-float\|Float Image]] 
```md
![ryaneof-Jh_Xk8RQtG0-unsplash.jpg|float-left|300](/img/user/assets/ryaneof-Jh_Xk8RQtG0-unsplash.jpg)
Langkawi, officially known by its sobriquet Langkawi, the Jewel of Kedah (Malay: Langkawi Permata Kedah), is a duty-free island and an archipelago of 99 islands (plus five small islands visible only at low tide in the Strait of Malacca) located some 30 km off the coast of northwestern Malaysia and a few kilometres south of Ko Tarutao, adjacent to the Thai border. Politically, it is an administrative district of Kedah, with Kuah as its largest town. Pantai Cenang is the island's most popular beach and tourist area.
```

---

### Changing the picture from left to right
You can simply switch the picture from left to right. For the Float Callout and Float Image, simple change the modifier from `left` to `right`. For MC Callout, move the text block above the picture callout