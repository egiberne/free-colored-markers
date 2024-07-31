# STEP BY STEP

## Step 1
Add a `DOCTYPE html` declaration at the top of the document, and an `html` element after that. Give the `html` element a `lang` attribute with `en` as its value.

<details>
<summary>HTML snippet</summary>

```html
<!DOCTYPE html>
<html lang="en">
</html>
```
</details>



## Step 2
Nest a `head` element within the `html` element. Just after the `head` element, add a `body` element.

<details>
<summary>HTML snippet</summary>

```html
<!DOCTYPE html>
<html lang="en">
  <head></head>
  <body></body>
</html>
```
</details>


## Step 3
Remember that the `title` element gives search engines extra information about the page. It also displays the content of that `title` element in two more ways:

in the title bar when the page is open
in the browser tab for the page when you hover on it. Even if that tab is not active, once you hover on the tab, the title text is displayed.
Within the `head` element, nest a `title` element with the text `Colored Markers`.


<details>
<summary>HTML snippet</summary>

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Colored Markers</title>
  </head>
  <body></body>
</html>
```
</details>

## Step 4
The `charset` attribute specifies the character encoding used by the document. `utf-8` | *Unicode Transformation Format – 8-bit* is a character encoding standard used for electronic communication.

Inside the `head` element, nest a `meta` element with the attribute `charset` set to `utf-8`.

<details>
<summary>HTML snippet</summary>

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Colored Markers</title>
    <meta charset="utf-8">
  </head>
  <body></body>
</html>
```
</details>

## Step 5
You can have multiple `meta` elements on a web page. Each `meta` element adds information about the page that cannot be expressed by other `HTML` elements.

Add another `meta` element within the `head`. Give it a `name` attribute set to `"viewport"` and a `content` attribute set to `"width=device-width, initial-scale=1.0"` so your page looks the same on all devices.

<details>
<summary>HTML snippet</summary>

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Colored Markers</title>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
  </head>
  <body></body>
</html>
```
</details>

## Step 6


