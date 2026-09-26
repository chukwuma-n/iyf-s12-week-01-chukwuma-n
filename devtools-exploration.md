# Task 1.2: DevTools Exploration

## Website 1: Example Domain

URL: https://example.com

### 1. What HTML tags are used on the page?

The main HTML tags I identified using DevTools are:

* `<html>`
* `<head>`
* `<title>`
* `<link>`
* `<meta>`
* `<style>`
* `<body>`
* `<h1>`
* `<div>`
* `<p>`
* `<a>`

### 2. What is the page title?

The page title is:

**Example Domain**

It is defined by the `<title>` element:

```html
<title>Example Domain</title>
```

### 3. How many headings are there?

There is **1 heading** on the page:

```html
<h1>Example Domain</h1>
```

---

## Website 2: MDN Web Docs

URL: https://developer.mozilla.org

### 1. Find the navigation menu — what tag is it wrapped in?

The navigation menu is wrapped in a:

```html
<nav>
```

element.

I found:

```html
<nav class="navigation" data-scheme="dark" data-open="false">
```

### 2. How is the search bar structured?

The search bar uses an HTML:

```html
<input>
```

element.

The `<input>` element is used to accept search text.

### 3. What happens when you hover over links?

When I move the mouse pointer over links, their text color changes.

For example, I observed that the **Learn** link changes to a brown color when hovered. Other links, such as **Tools**, also change color, although the hover color can be different depending on the link's styling.

---

## Website 3: httpbin Form

URL: https://httpbin.org/forms/post

### 1. Identify 5 different HTML elements

I identified the following HTML elements using DevTools:

1. `<form>`
2. `<p>`
3. `<fieldset>`
4. `<legend>`
5. `<label>`

I also identified other form elements including `<input>`, `<textarea>`, and `<button>`.

### 2. Find a form element and list its inputs

I found a `<form>` element containing form controls.

One input I identified was:

```html
<input type="time" min="11:00" max="21:00" step="900" name="delivery">
```

This input is used for the **preferred delivery time**.

Other form controls I identified were:

```html
<textarea name="comments"></textarea>
```

This is used for **delivery instructions**.

There was also:

```html
<button>Submit order</button>
```

which is used to submit the form.

### 3. Screenshot of the Elements/Inspector panel

I took a screenshot of the Firefox **Inspector** panel showing the HTML form and its form controls.

> Note: Firefox calls the Elements panel **Inspector**.
