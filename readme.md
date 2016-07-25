# HTML/CSS Review

This is a review of your working knowledge of HTML and CSS. Note that this review is designed to help you recall and familiarize yourself with technical concepts.

## Getting Started

* Fork and clone this repository
* Answer the following questions by...
  * Opening this file in Sublime
  * Answering the questions via Markdown. Feel free to refer to this [Markdown Cheat Sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
* Commit your changes
* Make a pull request for submission

---

## HTML

1.) Create a valid, empty HTML page with the necessary tags.

```html
<!DOCTYPE html>
<html>
<head>
  <title></title>
</head>
<body>

</body>
</html>
```

2.) What are the differences between these tags?

```html
<!-- Tag 1 -->
<img src="images/me.jpg" alt="My profile image">

<!-- Tag 2 -->
<div></div>
```

```
Tag one is am img and the src command will grab the desinated image to display on the page.
Tag two is a div. It desinates an area on the page, a section, that can be filled with other things.
```

---

## CSS

1.) Compare and contrast the following ways to add CSS to HTML elements.

```html
<!-- Inline CSS -->
<div style="background-color: red;"></div>

<!-- Internal style sheet -->
<style type="text/css">
  div {
    background-color: red;
  }
</style>

<!-- External style sheet (not shown) -->
<link rel="stylesheet" type="text/css" href="css/style.css">
```

```
Inline CSS is style written right in the code. It has to be written out every time it is used, but will override other CSS commands.

Internal style sheet is a section of the html that adds style choices to the page. Styles can be applied to an id, class, or tag. The entire style is written in the html page.

External style sheet is a link to an additional document that has all of your style commands. It keeps the html simpler and allows the same style to be used acros multiple pages.
```

2.) Below are some different CSS selectors. Use CSS comments to describe what each selector will do.

```css
/* comment like this */
div {
  border-radius: 50%;
}
/* will make all div objects have a border that is a circle */

.header p {
  font-size: 18px;
}
/* any text that is ina p tag, paragraph, in a header class to 18 pixels. */

.footer {
  position: absolute;
  bottom: 0;
}
/* class footer will be at the bottom of the page, 0 pixels from the bottom, and the absolute will make it on top of any other objects that might over lap. */

.splash-image {
  background-image: url("../images/ocean.jpg");
  background-size: cover;
  width: 100%;
}
/* anything that is class 'splash-image' will have the assinged image as a background and it will fully fill the area */

.ninja:hover {
  display: none;
  color: black;
}
/* when the mouse is on top of/hovers on anything with the class ninja, will have black text, but witht the display: none, will not be visable.
```


---

## Licensing
1. All content is licensed under a CC-BY-NC-SA 4.0 license.
2. All software code is licensed under GNU GPLv3. For commercial use or alternative licensing, please contact legal@ga.co.
