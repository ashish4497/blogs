---
title: "Responsive Web Design"
description: "A responsive website has a fluid and flexible layout which adjusts according to screen size. The importance of responsive web design is…"
date: "2020-02-14T14:10:07.813Z"
categories: []
published: true
canonical_link: https://medium.com/@ak8393267/responsive-web-design-1d3e8de55482
redirect_from:
  - /responsive-web-design-1d3e8de55482
---

![[https://www.google.com/url?sa=i&url=https%3A%2F%2Fsmallbiztrends.com%2F2013%2F05%2Fwhat-is-responsive-web-design.html&psig=AOvVaw2wrtcs8enycf0EnEfpDwpF&ust=1581135140737000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCOit197JvucCFQAAAAAdAAAAABAD](https://www.google.com/url?sa=i&url=https%3A%2F%2Fsmallbiztrends.com%2F2013%2F05%2Fwhat-is-responsive-web-design.html&psig=AOvVaw2wrtcs8enycf0EnEfpDwpF&ust=1581135140737000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCOit197JvucCFQAAAAAdAAAAABAD)](./asset-1.jpeg)

A responsive website has a fluid and flexible layout which adjusts according to screen size. The importance of responsive web  design is that it offers an optimized browsing experience. Basically, your website will look great and work well on a desktop (or laptop), a tablet, and a mobile phone’s browser. The aim of responsive to make the website user-friendly.

### Responsive vs. Adaptive vs. Mobile

Responsive Web Design provides the optimal viewing experience of a website, no matter what type of device the user is seeing it on. Adaptive web design is different from responsive design in that there isn’t one layout that always changes. Instead, there are several distinct layouts for multiple screen sizes. And the layout used depends on the screen size used. Adaptive web design is different from responsive design in that there isn’t one layout that always changes. Instead, there are several distinct layouts for multiple screen sizes. And the layout used depends on the screen size used.

### Media Query

Media features identify what attributes or properties will be targeted within the media query expression. It helps us to rewrite the layout and make it responsive.

```
@media all and (min-width: 800px) and (max-width: 1024px) {...}
```

### Mobile First

The mobile-first approach using to target the small viewport. The reason behind the mobile-first design there are numbers of mobile users.

### Viewport

The viewport is the user’s visible area of a web page. The viewport fixed-size web pages were too large to fit the viewport. To fix this, browsers on those devices scaled down the entire web page to fit the screen.

A `<meta>` viewport element gives the browser instructions on how to control the page's dimensions and scaling.

The `width=device-width` part sets the width of the page to follow the screen-width of the device (which will vary depending on the device).

The `initial-scale=1.0` part sets the initial zoom level when the page is first loaded by the browser.

```
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```
