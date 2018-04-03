---
layout: default
---

# HTML basics

## What does HTML stands for?

HTML stands for **H**yperText **M**arkup **L**anguage.

> **What is Hypertext?**
>
> Hypertext is text which contains links to other texts.

## How can I write an HTML empty page?
```html
//A blank HTML page.

<!DOCTYPE html>
<html>
</html>
```

> **What is `<!DOCTYPE html>` used for?**
>
> It tells the browser that it is HTML code.
>
> **What is `<html></html>`?**
>
> Things inside `<>` are called tags. The first is the HTML opening tag, while the second is the HTML closing tag.

## How can I write an HTML empty page with informations about the HTML file?
```html
//A blank HTML page with informations about the HTML file.

<!DOCTYPE html>
<html>
  <head>
    <title>
      HTML project title
    </title>
  <head>
</html>
```

> **What is `<head>` tag used for?**
>
> It is used to insert informations about the HTML file.
>
> **What kind of information `<title>` tag allow to insert?**
>
> It is useful to insert the bar title, and the html file/project title.

## How can I write an HTML page with contents?
```html
//An HTML page with contents.

<!DOCTYPE html>
<html>
  <head>
    <title>
      HTML project title
    </title>
  <head>
  <body>
    <h1>Title</h1>
  </body>
</html>
```

> **What is `<body>` tag used for?**
>
> It the used to tell the browser that inside the tag there is the HTML page content.
>
> **What kind of content `<h1>` tag allow to insert?**
>
> It is useful to insert the primary headings.

## How can I write an HTML page with headings of different sizes?
```html
//An HTML page with headings of different sizes.

<!DOCTYPE html>
<html>
  <head>
    <title>
      HTML project title
    </title>
  <head>
  <body>
    <h1>Biggest title</h1>
    <h6>Smallest title</h6>
  </body>
</html>
```

> **What is the difference between `<h1>` tag and `<h6>` tag?**
>
> There are several heading size, from <h1> to <h6>. So, <h1>,<h2>,<h3>,<h4>,<h5>,<h6>; from the biggest one to the smallest.

## How can I write an HTML page with a paragraph?
```html
//An HTML page with headings of different sizes.

<!DOCTYPE html>
<html>
  <head>
    <title>
      HTML project title
    </title>
  <head>
  <body>
    <h1>Title</h1>
	<p>Paragraph<p>
  </body>
</html>
```

> **What kind of content `<p>` tag allow to insert?**
>
> It is useful to insert the text inside a paragraph.

[Back](./)
