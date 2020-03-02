---
title: "About Flexbox"
description: "Flexbox is a new layout mode in CSS3. It helps us to design the items. Flex provides us with more efficiency to design elements."
date: "2020-02-04T15:58:32.693Z"
categories: []
published: true
canonical_link: https://medium.com/@ak8393267/about-flexbox-d1a3ebed1108
redirect_from:
  - /about-flexbox-d1a3ebed1108
---

Flexbox is a new layout mode in CSS3. It helps us to design the items. Flex provides us with more efficiency to design elements.

![](./asset-1.jpeg)

**inline-flex** This value causes an element to generate an inline-level _flex container_ box.

**flex** This value causes an element to generate a block-level _flex container_ box.

**Terminology:(Flex Container and Flex Items)**

![[https://www.google.com/url?sa=i&url=https%3A%2F%2Ftympanus.net%2Fcodrops%2Fcss\_reference%2Fflexbox%2F&psig=AOvVaw02K0NpxH\_yBPrCLVee6K12&ust=1580906905826000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCMi54Kf3t-cCFQAAAAAdAAAAABAN](https://www.google.com/url?sa=i&url=https%3A%2F%2Ftympanus.net%2Fcodrops%2Fcss_reference%2Fflexbox%2F&psig=AOvVaw02K0NpxH_yBPrCLVee6K12&ust=1580906905826000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCMi54Kf3t-cCFQAAAAAdAAAAABAN)](./asset-2.png)

**Flex Container** Parent element where we apply “display: flex”

**Flex Items** This is a children element inside the flex container.

**Flex Direction**

![[https://www.google.com/url?sa=i&url=https%3A%2F%2Ftympanus.net%2Fcodrops%2Fcss\_reference%2Fflexbox%2F&psig=AOvVaw02K0NpxH\_yBPrCLVee6K12&ust=1580906905826000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCMi54Kf3t-cCFQAAAAAdAAAAABAN](https://www.google.com/url?sa=i&url=https%3A%2F%2Ftympanus.net%2Fcodrops%2Fcss_reference%2Fflexbox%2F&psig=AOvVaw02K0NpxH_yBPrCLVee6K12&ust=1580906905826000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCMi54Kf3t-cCFQAAAAAdAAAAABAN)](./asset-3.png)

Flix Direction helps us to determine the direction of the item. By default, the flex items are horizontally aligned. There are two terminologies for example `main-axis and cross-axis`.

**Main Axis** By default in the flexbox flex items is aligned horizontally.

Cross Axis The cross-axis items are aligned vertically from top to bottom.

### flex-direction

The flex-direction properties help us to specify the how the flex items are palced in flex container. The flex-direction property can accept four values

```
flex-direction: row || column || row-reverse || column-reverse;
```![[https://www.google.com/url?sa=i&url=https%3A%2F%2Ftympanus.net%2Fcodrops%2Fcss\_reference%2Fflexbox%2F&psig=AOvVaw3jQk4Z3TAciuLFQ9o1UYGp&ust=1580908171674000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCPD8poL8t-cCFQAAAAAdAAAAABAD](https://www.google.com/url?sa=i&url=https%3A%2F%2Ftympanus.net%2Fcodrops%2Fcss_reference%2Fflexbox%2F&psig=AOvVaw3jQk4Z3TAciuLFQ9o1UYGp&ust=1580908171674000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCPD8poL8t-cCFQAAAAAdAAAAABAD)](./asset-4.jpeg)

### flex-wrap

The _flex-wrap_ property controls whether the flex container is _single-line_ or _multi-line._The `flex-wrap` property comes with three different values

```
flex-wrap: nowrap || wrap || wrap-reverse;
```![[https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.pinterest.com%2Figgil9191%2Fcss%2F&psig=AOvVaw37tn6532ctmbg77\_\_SzGxm&ust=1580908378659000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCPDB0un8t-cCFQAAAAAdAAAAABAD](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.pinterest.com%2Figgil9191%2Fcss%2F&psig=AOvVaw37tn6532ctmbg77__SzGxm&ust=1580908378659000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCPDB0un8t-cCFQAAAAAdAAAAABAD)](./asset-5.png)

### flex-flow

The _flex-flow_ property is a shorthand for setting the _flex-direction and flex wrap._ This property accepct two values flex-direction and flex-wrap.

### flex-order

This property allow to reorder the flex items without changing the source code of HTML.

![[https://www.google.com/url?sa=i&url=https%3A%2F%2Ftympanus.net%2Fcodrops%2Fcss\_reference%2Fflexbox%2F&psig=AOvVaw08ue6-3OnV6CduKgkSjL3y&ust=1580908665395000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCIDjjYL-t-cCFQAAAAAdAAAAABAD](https://www.google.com/url?sa=i&url=https%3A%2F%2Ftympanus.net%2Fcodrops%2Fcss_reference%2Fflexbox%2F&psig=AOvVaw08ue6-3OnV6CduKgkSjL3y&ust=1580908665395000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCIDjjYL-t-cCFQAAAAAdAAAAABAD)](./asset-6.png)

### Justify Content

justify content items will be lies on main-axis.It helps distribute extra free space leftover when either all the _flex items._The `justify-content` property can take 6 different values are

```
justify-content: flex-start || flex-end || center || space-between || space-around || space-evenly;
```![[https://www.google.com/url?sa=i&url=https%3A%2F%2Fopenclassrooms.com%2Fen%2Fcourses%2F5295881-create-web-page-layouts-with-css%2F5415181-align-items-and-justify-content&psig=AOvVaw0J\_vCqEClZ\_MgnOXN8AAN8&ust=1580917415288000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCKC1oL2euOcCFQAAAAAdAAAAABAD](https://www.google.com/url?sa=i&url=https%3A%2F%2Fopenclassrooms.com%2Fen%2Fcourses%2F5295881-create-web-page-layouts-with-css%2F5415181-align-items-and-justify-content&psig=AOvVaw0J_vCqEClZ_MgnOXN8AAN8&ust=1580917415288000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCKC1oL2euOcCFQAAAAAdAAAAABAD)](./asset-7.png)

### align-items

This property is similar to _justify-content. Align-items_ sets the default alignment for all of the flex container’s _items._

![[https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.slideshare.net%2Fzomigi%2Fcss3-layout%2F53-alignitems2011flexalign\_stretch\_stretch\_flexstart\_flexend&psig=AOvVaw3ldAeu-J6dBS4E3lqkQx0R&ust=1580917613457000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCKjf\_JufuOcCFQAAAAAdAAAAABAD](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.slideshare.net%2Fzomigi%2Fcss3-layout%2F53-alignitems2011flexalign_stretch_stretch_flexstart_flexend&psig=AOvVaw3ldAeu-J6dBS4E3lqkQx0R&ust=1580917613457000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCKjf_JufuOcCFQAAAAAdAAAAABAD)](./asset-8.jpeg)

### align-content

The align content property works on main-axis and align item work on the cross-axis. The `align-content` property accepts some different values

```
align-content: stretch || flex-start || flex-end || center || space-between || space-around;
```![[https://www.google.com/url?sa=i&url=https%3A%2F%2Fcss-tricks.com%2Fsnippets%2Fcss%2Fa-guide-to-flexbox%2F&psig=AOvVaw05eOrpY8NYQFMQbN53a1RO&ust=1580917842172000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCKCB6ImguOcCFQAAAAAdAAAAABAD](https://www.google.com/url?sa=i&url=https%3A%2F%2Fcss-tricks.com%2Fsnippets%2Fcss%2Fa-guide-to-flexbox%2F&psig=AOvVaw05eOrpY8NYQFMQbN53a1RO&ust=1580917842172000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCKCB6ImguOcCFQAAAAAdAAAAABAD)](./asset-9.png)
